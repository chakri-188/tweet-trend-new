pipeline {
    agent {
        node {
            label 'maven'
        }
    }
    
    stages {
        stage('Clone-code') {
            steps {
                git branch: 'main', credentialsId: 'maven-server-cred', url: 'https://github.com/chakri-188/tweet-trend-new.git'
            }
        }
    }
}