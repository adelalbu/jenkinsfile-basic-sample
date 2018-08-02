pipeline {
    agent any
    stages{
        stage('Create'){
            steps{
                sh '''
                cd ..
                
                cd git
                pwd
                ls
                touch ${STAGE_NAME}.aaaa
                ls
                '''
            }
        }
    }
}
