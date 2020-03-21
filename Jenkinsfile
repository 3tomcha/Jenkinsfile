pipeline {
    agent any 
    environment {
        AWS_ACCESS_kEY_ID = credentials('jenkins-aws-secret-key-id')    
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')    
    }
    stages {
        stage('Example Stage1') {
            steps {
                echo "step"
            }
        }
    }
}
