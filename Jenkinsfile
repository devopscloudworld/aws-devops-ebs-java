pipeline {
    agent any

    stages {
        stage('Checkout Github repo') {
            steps {
                echo 'Checkout my repo....'
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github', url: 'https://github.com/devopscloudworld/aws-devops-ebs-java.git']])
            }
        }
        
        
     stage('Build the project') {
            steps {
                echo 'Hello World'
            }
        }
        
        
    }
}
