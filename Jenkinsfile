pipeline {
    agent any

    stages {
        stage('Test backend') {
            steps {
                dir('backend') {
                    sh 'npm test'
                }
            }
        }

        stage('Check frontend') {
            steps {
                sh 'node --check frontend/src/main.js'
            }
        }
    }
}