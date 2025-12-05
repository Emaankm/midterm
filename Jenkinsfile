pipeline {
    agent any
    environment {
        DOCKER_IMAGE = "yourusername/hotel-interface:latest"
    }
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/yourusername/hotel-interface.git'
            }
        }
        stage('Run Tests') {
            steps {
                sh 'echo "No real tests yet, just a placeholder"'
            }
        }
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t $DOCKER_IMAGE .'
            }
        }
        stage('Run Docker Container') {
            steps {
                sh 'docker run -d -p 5000:80 $DOCKER_IMAGE'
            }
        }
    }
}
