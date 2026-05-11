pipeline {
    agent any

    stages {

        stage('Clone Verification') {
            steps {
                echo 'Repository cloned successfully'
            }
        }

        stage('Workspace Info') {
            steps {
                sh 'pwd'
                sh 'ls -l'
            }
        }

        stage('Execute Script') {
            steps {
                sh 'bash hello.sh'
            }
        }

        stage('System Information') {
            steps {
                sh 'whoami'
                sh 'hostname'
                sh 'date'
            }
        }
    }
}
