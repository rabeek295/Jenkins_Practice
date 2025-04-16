pipeline {
    agent{
        label 'Slave_node_Worker'
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
