pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'mvn clean install'
                sh 'java -jar target/spring-boot-initial-0.0.1-SNAPSHOT'
            }
        }
    }
}
