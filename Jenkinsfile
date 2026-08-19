pipeline {
    agent any

    stages {
        stage('Test Webhook') {
            steps {
                echo "GitHub webhook triggered Jenkins!"
                echo "Build number: ${BUILD_NUMBER}"
                sh 'echo "Time: $(date)"'
            }
        }
    }
}
