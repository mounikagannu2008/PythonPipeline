
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/mounikagannu2008/PythonPipeline.git'
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
