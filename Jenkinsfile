pipeline {
    agent any

    stages {
        stage('Fetch Code') {
            steps {
                echo 'Code fetched successfully!'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t my-app-image .'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment successful!'
            }
        }
    }
}
