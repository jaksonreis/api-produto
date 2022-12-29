pipeline {
    agent any

    stages {
        stage ('Bild Image') {
            steps {
                script {
                    dockerapp = docker.build("jaksonreis/api-produto", '-f ./src/Dockerfile ./src')
                }
                echo "Iniciando a Pipeline"            
            }
        }

    }
}