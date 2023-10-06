pipeline {
    agent {node { label 'mohan'}}
    stages{
        stage('install deoendecies'){
            steps{
                sh ' npm install'
            }


        }
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