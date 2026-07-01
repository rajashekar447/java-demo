stage('SonarQube Analysis') {
    steps {
        withSonarQubeEnv('sonarqube') {
            sh '''
                mvn sonar:sonar \
                -Dsonar.projectKey=raja.java-demo \
                -Dsonar.host.url=http://localhost:9000 \
                -Dsonar.login=sqp_a509fa0ac3176b7b110309ee951967e04cb27f62
            '''
        }
    }
}
