pipeline {
    agent any 
    environment {
        GITHUB_COMMON_CREDS = credentials('github')    
    }
    stages {
        stage('Example Stage1') {
            steps {
                sh 'curl -u ${env.GITHUB_COMMON_CREDS_USR}:${env.GITHUB_COMMON_CREDS_ID} 'https://api.github.com/user/repos''
            }
        }
    }
}
