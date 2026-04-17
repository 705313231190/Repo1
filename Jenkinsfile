pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git url: 'https://github.com/705313231190/Repo1.git', branch: '2026Q1'
            }
        }

        stage('Build') {
            steps {
                echo "Building project..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying project..."
            }
        }

    }
}
