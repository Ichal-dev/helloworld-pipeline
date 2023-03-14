pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "hello Build"
                sh './mvnw clean install'
            }
        }
        stage('Test') {
            steps {
                echo "mvn test"
            }
        }
        stage('Deploy') {
            steps {
                echo "hello Deploy"
            }
        }
    }
}