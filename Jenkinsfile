pipeline {
    agent{
        label 'slave_node'
    }
    stages {
        stage('print server info') {
            steps {
                sh """
                whoami
                uptime
                pwd
                echo ${env.HOSTNAME}
                """
            }
        }
    }
}
