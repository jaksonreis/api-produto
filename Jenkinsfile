pipeline {
    agent any

    stages {
        stage ('Bild Image') {
            steps {
                script {
                    dockerapp = docker.build("jaksonreis/api-produto:${env.BUILD_ID}", '-f ./src/Dockerfile ./src')
                }
                echo "Iniciando a Pipeline"            
            }
        }

    }
}