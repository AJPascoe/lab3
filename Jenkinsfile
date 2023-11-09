pipeline {
    agent any
    stages {
        stage('Build Stage'){
            steps {
                sh "chmod +x buildstage.sh"
                sh "sh buildstage.sh"
            }
        }
        stage('Test stage'){
            steps {
                sh "chmod +x teststage.sh"
                sh "sh teststage.sh"
            }
        }
        stage('Deploy stage'){
            steps {
                sh "chmod +x deploystage.sh"
                sh "sh deploystage.sh"
            }
        }
    }
}
