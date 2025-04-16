pipeline {
    agent{
        label 'Slave_node'
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
