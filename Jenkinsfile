pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'YOUR_GITHUB_URL'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Project...'
            }
        }
    }
}
