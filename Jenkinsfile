pipeline {
    agent any 
    stages {
        stage('Example Stage1') {
            environment {
                GITHUB_COMMON_CREDS = credentials('github')    
            }
            steps {
                sh 'curl -u ${GITHUB_COMMON_CREDS_USR}:${GITHUB_COMMON_CREDS_ID} 'https://api.github.com/user/repos''
            }
        }
    }
}
