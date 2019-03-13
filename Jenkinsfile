pipeline {
    agent any

    stages {
        stage('stop filebeat') {
            steps {
               sh 'sudo systemctl stop filebeat'
            }
        }
        stage('update filebeat') {
            steps {
                sh 'sudo yum update -y filebeat'
            }
        }
    }
}
