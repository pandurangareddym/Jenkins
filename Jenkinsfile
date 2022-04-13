pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}


pipeline {
    agent { docker { image 'php:8.1.0-alpine' } }
    stages{
        stage('build'){
            steps{
                sh 'php --version'
            }
        }
    }
}

pipeline {
    agent { docker {image 'golang:1.17.5-alpine' } }
    stages{
        stage{'build'} {
            step {
                sh 'go version'
            }
        }
    }
}