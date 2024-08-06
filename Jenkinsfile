pipeline {
    agent any

    stages {
        stage('Python Version') {
            steps {
                sh 'python3 --version'
            }
        }

        stage('Run Python Tests') {
            steps {
                sh 'python3 test.py'
            }
        }

        stage('Node.js Version') {
            steps {
                sh 'node --version'
                sh 'npm --version'
            }
        }

        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Run React Tests') {
            steps {
                sh 'npm test'
            }
        }
    }
}

