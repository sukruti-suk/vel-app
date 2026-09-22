pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo "Running on branch: ${env.BRANCH_NAME}"
            }
        }
        stage('Build') {
            steps {
                echo "Building application..."
            }
        }
        stage('Test') {
            steps {
                echo "Testing application..."
            }
        }
    }
}
// testing multi-branch
