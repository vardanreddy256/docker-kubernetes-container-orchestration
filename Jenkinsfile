pipeline {
    agent any

    stages {

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t vardan3236/flask-k8s-app .'
            }
        }

        stage('Push Docker Image') {
            steps {
                sh 'docker push vardan3236/flask-k8s-app'
            }
        }

        stage('Deploy to Kubernetes') {
            steps {
                sh 'kubectl apply -f deployment.yaml'
                sh 'kubectl apply -f service.yaml'
            }
        }

    }
}
