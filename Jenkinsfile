pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                echo 'Hello, Jenkins!'
                git checkout scm
            }
        }
        
        stage('Build') {
            steps {
                // Your build commands go here
                echo 'Building the project...,'
            }
        }
    }
    
    post {
        success {
            echo 'The pipeline has succeeded!'
        }
        failure {
            echo 'The pipeline has failed!'
        }
    }
}
