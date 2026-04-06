pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git 'https://github.com/SUBA-25/call-booking-application.git'
            }
        }

        stage('Build') {
            steps {
                sh 'docker-compose build'
            }
        }

        stage('Deploy') {
            steps {
                sh 'docker-compose up -d'
            }
        }
    }
}