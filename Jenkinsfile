def singlyQuoted = 'Hello'
pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                echo "BUILDIDは ${env.BUILDID} on ${env.JENKINS_URL}"
            }
        }
    }
}
