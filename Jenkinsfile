pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from Git repository
                git 'https://github.com/PriyankaDharade/mygitproject.git'
            }
        }

        stage('Build') {
            steps {
                // Simulate build step
                echo 'Building the project...'
                sh 'echo Build successful!'
            }
        }

        stage('Test') {
            steps {
                // Simulate test step
                echo 'Running tests...'
                sh 'echo Tests passed!'
            }
        }
    }

    post {
        always {
            echo 'Pipeline finished!'
        }
        success {
            echo 'Pipeline succeeded!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
