def singlyQuoted = 'Hello'
pipeline {
    agent any
    environment {
        CC = 'clang'
    }
    stages {
        stage('Deploy') {
            steps {
                sh 'printenv'
            }
        }
    }
}
