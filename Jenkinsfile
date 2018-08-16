pipeline {
    agent any
    stages {
        stage('One') { 
            steps {
                sh 'Test: npm install' 
            }
        }
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}