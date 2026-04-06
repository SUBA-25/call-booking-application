pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'development', url: 'https://github.com/SUBA-25/call-booking-application.git'
            }
        }

        stage('Build') {
            steps {
                echo "Build stage running..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy stage running..."
            }
        }
    }
}
