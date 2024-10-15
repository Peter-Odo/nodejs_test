pipeline {
    agent any
    stages {
        stage('Build node_modules for dev-one') {
            steps {
                echo 'npm install dev-one'
            }
        }
        stage('Run UTs') { 
            steps {
                echo 'npm test for dev-one'
            }
        }
    }
}