def singlyQuoted = 'Hello'
pipeline {
    agent any
    environment {
        CC = 'clang'
    }
    stages {
        stage('Example') {
            environment {
                DEBUG_FLAGS = -1
            }
            steps {
                sh 'printenv'
            }
        }
    }
}
