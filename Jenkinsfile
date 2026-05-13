pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building application using Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running JUnit and Mockito tests'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analysing code using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Scanning vulnerabilities using Snyk'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying application to AWS EC2 staging server'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running Postman integration tests on staging'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying application to AWS EC2 production server'
            }
        }
    }
}