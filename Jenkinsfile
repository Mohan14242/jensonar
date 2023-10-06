pipeline {
    agent {node { label 'mohan'}}
   
    stages{       
        stage('unit test'){
            steps{
                echo "unit testin gis done here"
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
            deleteDir()
        }
    }
}