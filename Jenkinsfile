pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo "Building Webpage..."
                sh 'ls -la'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy Stage (dummy for now)."
            }
        }
    }

    post {
        success {
            echo "Pipeline Successful!"
        }
    }
}

