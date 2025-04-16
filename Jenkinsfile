pipeline {
    agent any
        tools{
            maven'maven'
    stages {
        stage('maven project') {
            steps {
                mvn'clean package' 
            }
        }
    }
}
