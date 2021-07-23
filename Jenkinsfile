pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'kubectl get pods --kubeconfig=/root/kube/admin.conf'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}