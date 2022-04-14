pipeline {
    agent any 
    tools { 
        maven 'Maven 3.3.9'
        jdk 'jdk8'
    }
    stages {
        stage("Initialization") {
            steps{
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}
                '''       
            }
        }
        stage("Builds") {
            steps {
                echo "Hello World"
            }
        }
        stage("Testing") {
            steps{
                echo "Hello I am testing"
            }
        }
        stage("implementing") {
            steps{
                echo " I am implementind "
            }
        }
        stage("Deploying") {
            steps{
                echo "Deploying data"
            }
        }

    }
}