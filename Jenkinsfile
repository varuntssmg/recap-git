pipeline {
    agent {
        label 'slave'
    }

    stages {
        stage('Print Hostname') {
            steps {
                sh 'hostname'
            }
        }

        stage('IP Address') {
            steps {
                sh 'hostname -I'
            }
        }

        stage('CPU Details') {
            steps {
                sh 'lscpu'
            }
        }

        stage('Disk Usage') {
            steps {
                sh 'df -h'
            }
        }

        stage('Memory Usage') {
            steps {
                sh 'free -m'
            }
        }
         stage('date') {
            steps {
                sh 'date'
            }
        }
    }
}
