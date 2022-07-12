//Jenkinsfile (Declarative Pipeline)
pipeline {
    agent none
    stages {
        stage('build') {
            agent { docker { image 'php:8.1.4-alpine' } }
            steps {
                sh 'php --version'
                sh 'echo test'
            }
        }
    }
}
