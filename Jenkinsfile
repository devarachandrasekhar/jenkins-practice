pipeline {
    agent any

    stages {
        stage('Pull Code') {
            steps {
                echo 'Pulling code from Git...'
                echo 'Triggering through webhook'
            }
        }

        stage('Build') {
            steps {
                echo '🔹 Running build step...'
                sh 'echo Building the app...'
            }
        }

        stage('Deploy') {
            steps {
                echo '🔹 Deploying the app...'
                sh 'echo Deploying the app to server...'
            }
        }
    }
}
