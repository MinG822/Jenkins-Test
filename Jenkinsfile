pipeline {
        agent { docker {image 'python:2.5.1'}}
        stages {
            stage('build') {
                stpes {
                    sh 'python --version'
		    sh 'echo "Hello World"'
		    sh '''
		    	echo "Multiline shell workds too"
			ls -lah
			'''
                    }
                }
            }
        }
