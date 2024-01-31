pipeline {
    agent any
    
    stages {
        stage('First stage') {
            steps {
                echo 'Hello, Jenkins!'
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
