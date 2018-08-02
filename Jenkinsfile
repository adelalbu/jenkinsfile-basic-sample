pipeline {
    agent any
    stages{
        stage('Create'){
            steps{
                sh '''
                cd ..
                mkdir git
                cd git
                pwd
                ls
                touch ${STAGE_NAME}.new
                ls
                '''
            }
        }
    }
}
