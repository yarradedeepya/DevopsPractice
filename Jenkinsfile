pipeline {
    agent any
options {
    skipDefaultCheckout true
  }
   
stages {
        stage('Checkout') {
            steps {
                script{
                echo 'Hello, Jenkins!'
                git checkout scm
                }
            }
        }
        
        stage('Build') {
            steps {
                script{
                // Your build commands go here
                echo 'Building the project...,'
                }
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
