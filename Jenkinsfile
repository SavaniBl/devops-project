pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building Application'
            }
        }

        stage('Docker Build') {
            steps {
                bat 'docker build -t devops-project .'
            }
        }
    }
}