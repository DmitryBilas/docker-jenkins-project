pipeline {
    agent any

    stages {
        stage('DockerStage') {
            steps {
                sh '''
                    docker info
                '''

            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
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