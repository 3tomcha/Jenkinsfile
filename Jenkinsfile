pipeline {
    agent any 
    environment {
        GITHUB_COMMON_CREDS = credentials('github')    
    }
    stages {
        stage('Example Stage1') {
            steps {
                curl -u ${GITHUB_COMMON_CREDS_USR}:${GItHUB_COMMMON_CREDS_ID} 'https://api.github.com/user/repos'
            }
        }
    }
}
