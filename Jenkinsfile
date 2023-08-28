pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Check out the source code from the Git repository
                git clone "https://github.com/deepak77shinde/my-repos.git"
            }
        }

        stage('Build') {
            steps {
                echo "Build success"
            }
        }

        stage('Test') {
            steps {
               echo "Test success"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy"
            }
        }
    }

    
        
