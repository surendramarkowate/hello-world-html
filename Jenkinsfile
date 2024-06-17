pipeline {
    agent any
 
    stages {
        stage('Checkout') {
            steps {
                // Checkout the source code from GitHub
                git 'https://github.com/surendramarkowate/hello-world-html'
            }
        }
 
        stage('Build') {
            steps {
                // Perform build steps here if necessary
                sh 'echo "Build step: replace with actual build commands"'
            }
        }
 
        stage('Deploy') {
            steps {
                // Deployment steps (example: copying files to a server)
                sh 'echo "Deploy step: replace with actual deployment commands"'
            }
        }
    }
 
    post {
        always {
            // Clean up steps (if needed)
            sh 'echo "Post-processing: clean up or final steps"'
        }
    }
}
