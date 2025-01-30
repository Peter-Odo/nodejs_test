pipeline {
    agent any

    stages {
         stage('Checkout Code') {
            steps {
                echo 'https://github.com/Peter-Odo/nodejs_test.git'
            }
        }
        stage('Build node_modules') {
            steps {
                echo 'npm install'
            }
        }
        stage('Run UTs') { 
            steps {
                echo 'npm test'
            }
        }
        stage('Deploy GCP') { 
            steps {
               echo 'Deploying to GCP....'
            }
        }
    }
}
