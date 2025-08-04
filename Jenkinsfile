pipeline {
    agent any
    tools {
        maven 'maven' // This matches the name you gave in Jenkins
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}