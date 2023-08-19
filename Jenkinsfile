pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('Checkout') {
            steps {
                echo 'Checkout the code..'
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'b77961a9-eefe-4358-aa05-56d8e9a113f5', url: 'https://github.com/Ashokk111/ethansdemo1.git']])
            }
        }
         
    }
}
