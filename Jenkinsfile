
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'checking this out'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Python application'
            }
        }

        stage('Test') {
            steps {
                bat 'python app.py'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Application deployed successfully'
            }
        }
    }
}
