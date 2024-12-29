pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Add build commands here, e.g., mvn clean install
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add test commands here, e.g., running unit tests
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deployment steps here, e.g., docker run or SSH to a server
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
