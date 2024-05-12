pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/ankiiitGit/ABC_Organization.git'
            }
        }
        stage('Build') {
            steps {
                sh 'dotnet build' // Replace with your build command
            }
        }
        stage('Compile') {
            steps {
                sh 'dotnet compile' // Replace with your compile command
            }
        }
    }
}
