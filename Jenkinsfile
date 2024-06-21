pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                // Clone the repository
                git branch: 'main', url: 'https://github.com/casimirrex/jenkinsdemo.git'
            }
        }
        stage('Build') {
            steps {
                // Build your project
                sh 'echo "Building the project..."'
            }
        }
        stage('Test') {
            steps {
                // Run tests
                sh 'echo "Running tests..."'
            }
        }
        stage('Deploy') {
            steps {
                // Deploy the application
                sh 'echo "Deploying the application..."'
            }
        }
    }
}
