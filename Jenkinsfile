pipeline {
    agent any

    stages {
        stage('Build the app') {
            sh 'dotnet build'
        }
        stage('Test the app') {
            sh 'dotnet test'
        }
    }
}