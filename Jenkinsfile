pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'a2f8a5d5-2bda-426d-a44e-178833e1cfc3', url: 'https://github.com/sangaryousmane/cicd-playground.git']])
            }
        }
    }
}
