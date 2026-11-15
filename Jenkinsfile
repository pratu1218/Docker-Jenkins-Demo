pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                script {
                    bat 'docker build -t docker-jenkins-demo .'
                    echo 'Docker image built successfully!'
                }
            }
        }
    }
}
