pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                deleteDir()
            }
        }
        
        stage('Clone') {
            steps {
                checkout scm
            }
        }
        
        stage('Build') {
            steps {
                sh "mvn clean"
            }
        }
        
    }
}
