pipeline {
    agent any

    stages {
        stage('Install Dependencies') {
            steps {
                nodejs('NodeJS 24') {   // exact NodeJS tool name
                    sh 'npm install'
                }
            }
        }

        stage('Start Application') {
            steps {
                nodejs('NodeJS 24') {
                    sh 'npm start'
                }
            }
        }
    }
}
