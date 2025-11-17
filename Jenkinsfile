pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo "Cloning repository..."
                git branch: 'main',
                    url: 'https://github.com/syash4069-png/demo-public.git'
            }
        }

        stage('List Files') {
            steps {
                echo "Listing files..."
                sh 'ls -la'
            }
        }

        stage('Sleep') {
            steps {
                echo "Sleeping for 10 seconds..."
                sh 'sleep 10'
            }
        }

        stage('Run Script') {
            steps {
                echo "Running command..."
                sh 'echo "Pipeline Finished Successfully!"'
            }
        }

    }
}
