pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'npm install'
            }
        }
        stage('run') {
            steps {
                bat 'node index.js'
            }
        }
    }
}