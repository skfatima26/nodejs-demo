pipeline {
    agent any
    tools {
        nodejs "Nodejs 24"   // yaha tumhara setup ka exact name use karna
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

