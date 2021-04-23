pipeline {
    agent {
        docker {
            image 'python:3.5.1'
        }
    }
    stages {
        stage('Test') {
            steps {
                sh test_calc.sh
            }
        }
        stage('Build') {
            steps {
                sh 'echo "I want to see buid success"'
            }
        }
    }
}
