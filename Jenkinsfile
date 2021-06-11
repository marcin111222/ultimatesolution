pipeline {
    agent any
    environment {
        dotnet = "C:\\Program FIles\\dotnet\\dotnet.exe"
    }

    stages {
        stage('Build') {
            steps {
                bat 'dotnet build'
            }
        }
        stage('Run') {
            steps {
                bat 'dotnet run'
            }
        }
        stage('Clean') {
            steps {
                bat 'dotnet clean'
            }
        }
    }
}