pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: '989d82a1-e2ea-4c61-a473-60489a5e3838', url: 'https://github.com/zzx131/springbot-jenkins.git']]])
            }
        }
    }
}
