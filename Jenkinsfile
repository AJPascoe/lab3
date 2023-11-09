pipeline {
    agent any
    stages {
        stage('Build Stage'){
            steps {
                sh "sh buildstage.sh"
            }
        }
        stage('Test stage'){
            steps {
                sh "sh teststage.sh"
            }
        }
        stage('Deploy stage'){
            steps {
                sh "sh deploystage.sh"
            }
        }
    }
}
