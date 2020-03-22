pipeline {
    agent any 
    stages {
        stage('Example Stage1') {
            environment {
                GITHUB_COMMON_CREDS = credentials('github')    
            }
            steps {
                sh 'curl -i https://api.github.com/users/octocat/orgs'
            }
        }
    }
}
