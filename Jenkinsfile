pipeline {
    agent{
        label 'Slave_Node_Worker'
    }
    stages {
        stage('print server info') {
            steps {
                sh '''
                whoami
                uptime
                pwd
                echo ${env.HOSTNAME}
                '''
            }
        }
    }
}
