pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World chaz2"'
            }
        }
        stage('Deploy to Test') {
            steps {
                sh 'echo "Test Hello World!"'
            }
        }
        stage('Deploy to Stage') {
            steps {
                sh 'echo "Test Hello World!"'
            }
        }
        stage('Deploy to UAT') {
            steps {
                sh 'echo "Test Hello World!"'
            }
        }
        stage('Deploy to Production') {
            steps {
                sh 'echo "Test Hello World!"'
                sh 'pwd'
                sh 'free -m'
                sh 'df -h'
            }
        }
    }
}
