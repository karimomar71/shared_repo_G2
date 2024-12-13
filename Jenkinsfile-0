pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build stage'
                sh './mvnw clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Test the application...'
                sh './mvnw test'
            }
        }
    }
}
