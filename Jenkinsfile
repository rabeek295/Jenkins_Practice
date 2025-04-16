pipeline {
    agent any

    stages {
        stage('print server info') {
            steps {
                whoami
                uptime
                pwd
            }
        }
    }
}
