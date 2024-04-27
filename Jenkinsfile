pipeline {
    agent any
	stages {
        stage('Run Docker Compose') {
            steps {               
		sudo 'docker-compose up -d'
            }
        }        
    }
}
