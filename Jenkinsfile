pipeline {
    agent any 
     parlle
    stages {
        stage('Build') { 
            steps {
                echo " mave package build"
            }
        }
        stage('Test') { 
            steps {
                echo " Testing maven packag "
            }
        }
        stage('Deploy') { 
            steps {
               echo  " Deploying on Ec2 server"
            }
        }
    }
}
