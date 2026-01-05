pipeline {
    agent any
    stages {
        stage('Code Analysis') {
            steps {
               sh 'uname' 
            }
        }
        stage('Build') {
            steps {
                sh 'cat /etc/os-release'
            }
        }
        stage('Deploy Frontend') {
            steps {
                sh 'sudo docker image ls'
            }
        }
    }
}