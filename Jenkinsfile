pipeline {
    agent any
    



    

    
    stages {
        stage('Build') {
            steps {
                // Checkout your source code from version control (e.g., Git)
                echo 'Build!'
            }
        }

        stage('Test') {
            steps {
                // Run your tests here (e.g., unit tests, integration tests)
               echo 'Tested!'

            }
        }

        stage('Push') {
            steps {
                // Push the Docker image to a container registry (e.g., Docker Hub)
                 echo 'Pushed!'
            }
        }

        stage('Deploy') {
            steps {
                // Deploy your application (e.g., to a Kubernetes cluster)
                echo 'Deploy!'
            }
        }
    }

    post {
        success {
            // Notify on successful deployment (e.g., Slack, email, etc.)
            echo 'Deployment successful!'
        }
        failure {
            // Notify on pipeline failure
            echo 'Pipeline failed!'
        }


    }
}
