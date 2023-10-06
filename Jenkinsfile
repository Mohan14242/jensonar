pipeline {
    agent {node { label 'mohan'}}
   
    stages{       
        stage('unit test'){
            steps{
                echo "unit testin gis done here"
            }
        }
        stage('sonar scanner'){
            steps{
                sh 'sonar-scanner'
            }
        }
        stage('deployment'){
            steps{
                echo 'deploying the production'
            }
        }
    
    }
}