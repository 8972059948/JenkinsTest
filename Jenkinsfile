pipeline {
    agent any
    environment {
        CI = 'true'
    }
    stages {
        stage('One') {
            steps {
                echo 'npm install'
            }
        }

        stage('Build') {
            try {
                sh 'npm install'
            } catch(exc) {
                echo 'Something went worng!'
                throw
            }
        }

    }
}