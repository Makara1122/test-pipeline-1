pipeline {

    agent {
        docker {
            image 'maven:3.9.9-eclipse-temurin-21-alpine'
        }
    }

    stages {

        stage('Build') {
            steps {
                sh 'mvn --version'
            }
        }

        stage(' Print message ') {
            steps {
                echo 'Hello, World'
            }
        }
    }
}