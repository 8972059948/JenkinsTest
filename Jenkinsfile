pipeline {
    agent any
    stages {
        stage('One') { 
            steps {
                sh 'Test: npm install' 
            }
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}