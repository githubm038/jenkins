pipeline {
    agent any 
    stages {
        stage('Test') {
            steps {
                sh 'docker build -t node:16.13.1-alpine'
            }
        }
    }
}
