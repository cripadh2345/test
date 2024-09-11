pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'mvn clean install'
                sh 'java -jar /var/jenkins_home/workspace/maven-java-project/target/spring-boot-initial-0.0.1-SNAPSHOT'
            }
        }
    }
}
