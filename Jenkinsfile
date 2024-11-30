pipeline {
    agent {
        docker { image 'python3:latest' }
    }
    stages {
        stage('Version') { 
            steps {
                sh 'python3 --version'
            }
        }
    }
}
