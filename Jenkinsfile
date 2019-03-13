pipeline {
    agent any

    stages {
        stage('stop filebeat') {
            steps {
                sh 'sudo systemctl stop filebeat'
                sh 'sudo systemctl status filebeat'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
