pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git 'https://github.com/shriyadeo01/Employee-Management-System.git'
            }
        }

        stage('Build') {
            steps {
                bat 'python app.py'
            }
        }

        stage('Test') {
            steps {
                bat 'python test.py'
            }
        }
    }
}