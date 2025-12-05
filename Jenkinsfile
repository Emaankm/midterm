pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Emaankm/midterm.git'
            }
        }
        
        stage('Build') {
            steps {
                echo 'No build needed for frontend project'
            }
        }
        
        stage('Test') {
            steps {
                echo 'No tests available'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Frontend pipeline completed successfully!'
            }
        }
    }
}
