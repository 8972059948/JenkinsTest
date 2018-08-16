pipeline {
    agent any
    stages {
        stage('One') { 
            steps {
                echo 'Test: npm install' 
            }
        }
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}