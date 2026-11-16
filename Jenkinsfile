
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
               bat '"C:\\Users\\DELL\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" app.py'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Application deployed successfully'
            }
        }
    }
}
