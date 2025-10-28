pipeline {
    agent any

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
                bat '"C:\\Users\\pkavi\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" C:\\path\\to\\your_script.py'
            }
        }
    }
}
