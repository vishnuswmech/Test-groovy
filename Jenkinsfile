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
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}