pipeline {
    agent any 
    stages {
        stage('Example Stage1') {
            environment {
                GITHUB_COMMON_CREDS = credentials('github')    
                DATA = '{"name":"tomoya"}'            
            }
            steps {
                sh 'curl -u $GITHUB_COMMON_CREDS_USR:$GITHUB_COMMON_CREDS_PSW -d ${DATA} https://api.github.com/user/repos'
            }
        }
    }
}
