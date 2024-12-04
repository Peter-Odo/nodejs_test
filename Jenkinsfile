pipeline {
    agent any
    stages {
        stage('Build node_modules for Jenkins Master') {
            steps {
                echo 'npm install'
            }
        }
        stage('Run UTs for Jenkins') { 
            steps {
               echo 'npm run test'
            }
        }
        stage('Deploy to staging..') { 
            steps {
                echo 'Deploying to staging server: stage.devops.com'
            }
        }
        stage('Deploy to production..') { 
            steps {
                echo 'Deploying to production server: devops.com'
            }
        }
    }
}