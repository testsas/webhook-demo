pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo '🚀 Code received from GitHub!'
            }
        }
    }
    post {
        success {
            echo '✅ Build succeeded!'
        }
    }
}
