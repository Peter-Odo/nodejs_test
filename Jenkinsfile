pipeline {
    agent any
    stages {
        stage('Build node_modules for Jenkins Webhooks') {
            steps {
                echo 'npm install for Jenkins'
            }
        }
        stage('Run UTs for Jenkins') { 
            steps {
                echo 'npm test for Jenkins'
            }
        }
        stage('Deploy to staging..') { 
            steps {
                echo 'Deploying to staging server: stage.devops.com'
            }
        }
    }
}