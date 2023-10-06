pipeline {
    agent {node { label 'mohan'}}
    environment {
        NODEJS_HOME = tool(name: 'NodeJS', type: 'jenkins.plugins.nodejs.tools.NodeJSInstallation').getHome()
        PATH = "${NODEJS_HOME}/bin:${PATH}"
    }
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