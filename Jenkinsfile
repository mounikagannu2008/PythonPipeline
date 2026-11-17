
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'checking this out dude'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Python application'
            }
        }

        stage('Test') {
            steps {
               bat '"C:\\Users\\GVPW\\AppData\\Local\\Microsoft\\WindowsApps\\python.exe" app.py'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Application deployed successfully'
            }
        }
    }
}
