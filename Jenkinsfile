pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'mvn clean install'
                sh 'ls -la'
                cd '/target'
                sh 'ls -la'
                sh 'pwd'
            }
        }
    }
}
