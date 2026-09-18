pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Build - Build the code using Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Unit and Integration Tests - Run tests using JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Code Analysis - Analyse code using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Security Scan - Scan for vulnerabilities using OWASP Dependency-Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy to Staging - Deploy to AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Integration Tests on Staging - Run tests using Postman/Newman'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy to Production - Deploy to AWS EC2'
            }
        }
    }
}
