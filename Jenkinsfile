pipeline {
    agent any
    stages {
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
    }
}
