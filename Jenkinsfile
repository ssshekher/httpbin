pipeline {
 
    agent any
    
    stages {
      
      stage('Install Dependencies ') {
         steps {
            sh 'npm install'
         }
      }
      stage("Build") {
            steps {
                sh "npm run build"
            }
         }
      stage('Test stage Done') {
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
