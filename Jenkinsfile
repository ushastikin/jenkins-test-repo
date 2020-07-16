pipeline {
    agent {
        docker {
            image 'node:14-alpine'
            label 'docker'
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
