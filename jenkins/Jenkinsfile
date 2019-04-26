pipeline {
    agent any
	tools { 
        maven 'MAVEN' 
        jdk 'JAVA' 
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
        
    }
}
