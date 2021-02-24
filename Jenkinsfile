pipeline {
    agent any
    
    stages {
        stage('build') {
            steps {
            	sh 'pwd'
            	sh 'chmod +x gradlew'
	sh './gradlew bootJar'
            }
        }
    }
}