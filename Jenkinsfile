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
                kubectl('test') {
                    container('jenkins') {
                        sh 'kubectl get pods --kubeconfig=/root/kube/admin.conf'
                    }
                }
            }
        }
    }
}

            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}