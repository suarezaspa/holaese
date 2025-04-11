pipeline {
    agent any

    stages {
        stage('Clonar repositorio') {
            steps {
                echo 'Clonando el repo...'
            }
        }
        stage('Ejecutar script') {
            steps {
                sh 'chmod +x script.sh'
                sh './script.sh'
            }
        }
    }
}

