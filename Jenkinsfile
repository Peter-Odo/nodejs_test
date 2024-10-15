pipeline {
    agent any
    stages {
        stage('Build node_modules for fixes') {
            steps {
                echo 'npm install for fixes'
            }
        }
        stage('Run UTs for fixes') { 
            steps {
                echo 'npm test for fixes'
            }
        }
        stage('Deploy to staging..') { 
            steps {
                echo 'Deploying to staging server: stage.devops.com'
            }
        }
    }
}