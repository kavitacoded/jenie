pipeline {
    agent any

    environment {
        PATH = "C:\\Users\\pkavi\\AppData\\Local\\Programs\\Python\\Python313;${env.PATH}"
    }

    stages {
        stage('Checkout Code') {
            steps {
                echo 'Checking out source code...'
                checkout scm
            }
        }

        stage('Extract Data') {
            steps {
                echo 'Running Python script...'
                bat '"C:\\Users\\pkavi\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" C:\\path\\to\\python extract.py'
            }
        }
    }
}
