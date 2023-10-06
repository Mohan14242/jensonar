pipeline {
    agent {node { label 'mohan'}}
   
    stages{       
        stage('unit test'){
            steps{
                sh 'zip -r ./* --exclude=.git'
            }
        }
       
        stage('deployment'){
            steps{
                echo 'deploying the production'
            }
        }
    
    }
    post{
        always{
            echo "this was for cleaning"
            
        }
    }
}