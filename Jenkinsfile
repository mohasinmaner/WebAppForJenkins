pipeline {
    agent any
    tools {
        maven 'Maven 3.8.1'
    }
    stages {
        stage('Clean and Install') {
            steps {
               bat 'mvn clean install'
            }
        }
        stage('Package') {
            steps {
               bat 'mvn package'
            }
        } 
    }
}
