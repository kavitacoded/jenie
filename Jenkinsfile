pipeline{
    agent any{
        stage('Checkout Code'){
            steps{
                checkout scm
            }
        }
        stage('Extract Data'){
            steps{
                bat 'python extract.py'
            }
        }
    }
}