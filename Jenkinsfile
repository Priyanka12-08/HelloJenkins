pipeline {
    agent {
        docker { image 'maven:3.9.1-openjdk-17' }
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean compile'
            }
        }
    }
}