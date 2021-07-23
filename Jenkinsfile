pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'sudo docker run -dit centos:8'
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