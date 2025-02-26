pipeline {
    agent any
    tools {
        maven 'withMaven'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
        
           
                 
            
            
}}
