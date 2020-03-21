def singlyQuoted = 'Hello'
pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                echo "BUILD_IDは ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}
