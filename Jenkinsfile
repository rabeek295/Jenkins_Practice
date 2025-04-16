pipeline {
    agent any

    stages {
        stage('print server info') {
            steps {
                sh '''
                whoami
                uptime
                pwd
                '''
            }
        }
    }
}
