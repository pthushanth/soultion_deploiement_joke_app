pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                nodejs(nodeJSInstallationName: 'node_17') {
                    bat 'npm install'
                    bat 'npm run build'
                    bat 'npm run test'
                }
                
                
            }
        }
    
    }
}