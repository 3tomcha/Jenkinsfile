pipeline {
    agent any 
    stages {
        stage('Example Stage1') {
            environment {
                GITHUB_COMMON_CREDS = credentials('github')    
                DATA = '{"name":"tomoya"}'            
            }
            steps {
                bash 'curl -u $GITHUB_COMMON_CREDS_USR:$GITHUB_COMMON_CREDS_PSW -d ${env.DATA} https://api.github.com/user/repos'
            }
        }
    }
}
