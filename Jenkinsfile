pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                sh 'echo Build stage...'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo Deploy stage...'
            }
        }
    }
}
