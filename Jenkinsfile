pipeline {
    agent any
    tools {
        nodejs 'NodeJS 24'   // exact tool name
    }
    stages {
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }
        stage('Start Application') {
            steps {
                sh 'npm start'
            }
        }
    }
}

