pipeline {
    agent none
    stages {
        agent { docker { image 'maven:3.8.7-eclipse-temurin-11' } }
        stage('build') {
            steps {
                sh "echo 'chorizonnnnn!!!!!'"
                sh 'mvn --version'
            }
        }
    }
}