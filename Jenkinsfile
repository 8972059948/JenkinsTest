pipeline {
    agent any
    stages {
        stage('One') { 
            steps {
                echo 'Test: npm install' 
            }
        }
        stage('Two') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}