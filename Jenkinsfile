pipeline {
    agent any

    stages {
        stage('API build') {
            steps {
                echo 'Building..'
                sh 'dotnet publish -c Release -o handy.io api/Handy.io'
            }
        }
        stage('API stop and clear') {
            steps {
                echo 'Testing..'
            }
        }
        stage('API create') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('API deploy') {
            steps {
                echo 'Deploying....'
            }
        }

        stage('FRONT build') {
            steps {
                echo 'Building..'
            }
        }
        stage('FRONT stop and clear') {
            steps {
                echo 'Testing..'
            }
        }
        stage('FRONT create') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('FRONT deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}