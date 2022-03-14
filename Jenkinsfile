pipeline {
 
    agent any
    
    stages {
      
      stage('Install Dependencies ') {
         steps {
            sh 'npm install'
         }
      }
      
      stage('Test') {
        steps {
           sh 'echo "testing application...."'
        }
      }
        
         stage("Deploying complete") {
         steps {
           sh 'echo "deploying application...."'
         }
      }
    }
  }
