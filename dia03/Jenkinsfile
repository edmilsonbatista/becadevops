pipeline {
    agent any
   
    stages{
        stage('Sleep'){
            steps{
                sh 'sleep 20'
            }
        }
        stage('Checkout'){
            steps{
                echo "Checkout git"
            }
        }
        stage('Build'){
            steps{
                echo "Build da aplicação"
            }
        }
        stage('Deploy'){
            steps{
                echo "Deploy em produção"
            }
        }
    }
}
