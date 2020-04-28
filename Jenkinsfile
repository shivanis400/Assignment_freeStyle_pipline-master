pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('Stage 1 - ISPYTHON') {
            steps {
                sh 'python --version'
            }
        }
        stage('Building') {
            steps {
                sh 'python src/calsi.py'
            }
        }
         stage('Testing') {
            steps {
                sh 'python src/calsi.py'
            }
        }
         stage('Deploying') {
            steps {
                sh 'python src/calsi.py'
            }
        }
    }
}
