pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t mlops-lab6 .'
            }
        }

        stage('Run Training') {
            steps {
                sh 'docker run mlops-lab6'
            }
        }
    }
}
