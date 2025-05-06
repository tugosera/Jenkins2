pipeline {
    agent any

    stages {
        stage('Install Node.js and Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Run Express App') {
            steps {
                sh 'nohup npm start &'
            }
        }
    }
}
