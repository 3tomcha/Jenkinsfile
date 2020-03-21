def singlyQuoted = 'Hello'
pipeline {
    agent any
    environment {
        CC = """{${sh
                returnStdOut: true,
                script: 'echo "clang"'
              }}"""
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
