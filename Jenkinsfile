pipeline {
	agent any
	stages {
		stage('Install dependencies') {
			steps {
				sh "npm install"
				sh "npm install jest"
				}
			}

		stage('Run tests') {
			steps {
				sh "npm test"
				}
			}
		}
}
