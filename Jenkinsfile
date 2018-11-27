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
    }
}
