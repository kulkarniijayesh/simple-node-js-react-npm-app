pipeline {
    agent {
        docker {
            image 'node:12.8'
            args '-u root -p 3000:3000'
        }
    }
    stages {
        stage('Build'){
            steps {
                sh 'npm install'
            }
        }
    }
}