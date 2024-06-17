pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Clean up the workspace
                sh "make clean"

                // Build the project
                sh "make build"
            }
        }

        stage('Test') {
            steps {
                // Run tests
                sh "make test"
            }
        }

        stage('Deploy') {
            steps {
                // Deploy the application
                sh "make deploy"
            }
        }
    }

    post {
        always {
            // Clean up after the build
            sh "make clean"
        }
    }
}

// Scripts for build, test, and deployment
stage('Build') {
    // Execute code for building the project
}

stage('Test') {
    // Execute code for testing the project
}

stage('Deploy') {
    // Execute code for deploying the project
}
