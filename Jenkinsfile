pipeline {
    agent any
    stages {
        stage('Run app from docker-compose file.') {
            steps {
                sh 'docker compose up -d'
            }
        }
    }
}
