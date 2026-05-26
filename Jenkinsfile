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
                sh 'docker build -t devops-project .'
            }
        }
    }
}