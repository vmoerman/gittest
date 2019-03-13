pipeline {
    agent any

    stages {
        stage('stop filebeat') {
            steps {
                sh 'systemctl stop filebeat'
                sh 'systemctl status filebeat'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
