pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                echo "Pulling code from GitHub..."
                git url: 'https://github.com/USERNAME/REPO.git',
                    branch: 'main',
                    credentialsId: 'github_creds'
            }
        }

        stage('Build') {
            steps {
                echo "Running build steps..."
                // For HTML website, nothing to build
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                // Add real tests if available
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying website..."
                // Deployment logic if server exists
            }
        }
    }
}
