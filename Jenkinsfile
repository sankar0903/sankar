pipeline {
    agent any

    stages {
		stage('Scan') {
            steps {
                echo 'Scanning the code'
		eco 'java --version'
            }
        }
		stage('build') {
			agent {
				label 'Jenkins-test'
			}
     
        }
    }
}
