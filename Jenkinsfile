pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'git --version'
                sh 'curl --version'
            }
        }
    }
}