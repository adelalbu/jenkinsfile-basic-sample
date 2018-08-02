pipeline {
    agent any
    stages{
        stage('Create'){
            steps{
                sh '''
                pwd
                ls
                touch ${STAGE_NAME}.new
                ls
                '''
            }
        }
    }
}
