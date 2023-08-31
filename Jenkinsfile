pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from the Git repository
                checkout scm
            }
        }

        stage('Install Dependencies') {
            steps {
                // Install npm dependencies
                sh 'npm install'
            }
        }

        stage('Run Development Server') {
            steps {
                // Run the npm script to start the development server
                sh 'npm start'
            }
        }

        // Add more stages as needed
    }
}
