pipeline {
    agent { 
        docker {
            image 'python:2.5.1'
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'echo "Hello World"'
            }
        }
    }
}
