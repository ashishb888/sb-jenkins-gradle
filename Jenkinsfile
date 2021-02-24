pipeline {
    agent any
    
    stages {
        stage('deploy') {
            steps {
            	sh 'pwd'
            	sh 'chmod +x gradlew'
	sh './gradlew bootRun'
            }
        }
    }
}