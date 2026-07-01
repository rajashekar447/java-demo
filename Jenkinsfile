pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Source code downloaded from GitHub'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }

    }
}
