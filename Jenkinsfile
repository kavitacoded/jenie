pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                echo 'Checking out code...'
                checkout scm
            }
        }

        stage('Run Python Script') {
            steps {
                echo 'Executing Python script...'
                bat '"C:\\Users\\pkavi\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" extract_data.py'
            }
        }
    }
}
