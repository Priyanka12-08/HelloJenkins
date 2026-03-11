pipeline {
    agent any
    stages {
       stage ('Build') {
        steps {
            sh 'mvn clear compile'
        }
       }

       stage ('Test') {
        steps {
            sh 'mvn test'
        }
       }

       stage ('Package') {
        steps {
            sh 'mvn package'
        }
       }

    }
}