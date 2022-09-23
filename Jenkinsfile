pipeline {
    agent {   label 'Built-In' }
    stages {
        stage('Stage 1') {
            steps {
                sh '''
                ls
                pwd
                docker --version
                '''
            }
        }

    stage('Stage 2') {
            steps {
                sh '''
                ls
                pwd
                '''
            }
        }

    }
}