pipeline {
    agent { docker { image 'php:8.4.1-alpine3.21' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}