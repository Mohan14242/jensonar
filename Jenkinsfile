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
                sh 'mkdir /home/mohan'
            }
        }
    
    }
}