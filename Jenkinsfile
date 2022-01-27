pipeline {
    agent any 
    stages {
        stage('Git Clone') {
            steps {
                git 'https://github.com/githubm038/jenkins.git'
            }
        }
        stage('Test') {
            steps {
                sh 'sudo docker run node:16.13.1-alpine'
            }
        }
    }
}
