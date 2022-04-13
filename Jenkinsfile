pipeline {
    agent{
        docker { image 'maven:3.8.4-openjdk-11-slim'}
    }
    stages{
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}

pipeline {
    agent { docker { image 'node:16.13.1-alpine' } }
    stages {
        stage('build') {
        steps{
            sh 'node --version'
        }
      }
    }
}