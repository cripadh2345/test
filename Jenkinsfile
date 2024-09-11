pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'mvn clean install'
                sh 'ls -la'
                sh 'cd /target'
                sh 'ls -la'
                sh 'pwd'
            }
        }
    }
}
