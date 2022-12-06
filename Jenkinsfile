pipeline {
    agent any
    stages{
        stage('stage 1'){
            when {
                expression { choice == '1' }
            }
            
            steps{
                script{
                    sh 'echo "stage 1"'                   
                }
            }
        }
        stage('Stage 2'){
            when {
                expression { choice == '2' }
            }
            steps{
                script{       
                        sh 'echo "stage 2"'
                }
            }
        }
        stage('Stage 3'){
            when {
                expression { choice == '3' }
            }
            steps{
                script{       
                    sh 'echo "stage 3"'
                }
            }
        }
        stage('Stage 4'){
            when {
                expression { choice == '4' }
            }
            steps{
                script{
                    sh 'echo "stage 4"'
                }
            }
        }
    }
}
