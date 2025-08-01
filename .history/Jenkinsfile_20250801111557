pipeline {
    agent any
    stages {
        stage('Prepare'){
            steps {
                git credentialsId: 'HCH',
                    branch: 'main',
                    url: 'https://github.com/DooBae-KR/jenkins_study.git'
            }
        }
        stage('test') {
            steps {
                echo 'test stage'
            }
        }
        stage('build') {
            steps {
                echo 'build stage'
            }
        }
        stage('docker build') {
            steps {
                echo 'docker build stage'
            }
        }
    }
}