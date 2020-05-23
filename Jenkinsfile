pipeline {
    agent any
    stages {
       stage('Linting') {
      
       } 
        stage('Build image') {
            steps {
                echo 'Starting to build docker image'

                script {
                    def customImage = docker.build("my-image:${env.BUILD_ID}")
                    customImage.push()
                }
            }
        }
        stage('Push image') {
        }
        stage('set current kubectl context') {
         }
         stage('Deploy container') {
        }
    }
}


