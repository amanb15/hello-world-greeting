pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Code already checked out by Jenkins'
            }
        }

        stage('List Files') {
            steps {
                sh 'ls -l'
            }
        }

        stage('Print File') {
            steps {
                sh 'cat * || true'
            }
        }
    }
}
