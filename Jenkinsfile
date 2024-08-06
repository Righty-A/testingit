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
    }
}

