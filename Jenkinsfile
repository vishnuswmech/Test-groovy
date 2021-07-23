pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'sudo docker run -dit centos:latest'
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