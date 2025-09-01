pipeline {
    agent any

    triggers {
        pollSCM('* * * * *')
    }

    stages {
        stage('Build') {
            steps { echo 'Building the application...' }
        }

        stage('Unit and Integration Tests') {
            steps { echo 'Running unit and integration tests...' }
        }

        stage('Code Analysis') {
            steps { echo 'Analyzing code quality...' }
        }

        stage('Security Scan') {
            steps { echo 'Scanning for vulnerabilities...' }
        }

        stage('Deploy to Staging') {
            steps { echo 'Deploying to staging environment...' }
        }

        stage('Integration Tests on Staging') {
            steps { echo 'Running integration tests on staging environment...' }
        }

        stage('Deploy to Production') {
            steps { echo 'Deploying to production environment...' }
        }
    }
}
