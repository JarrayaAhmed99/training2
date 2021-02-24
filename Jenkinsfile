pipeline {
    agent {
        docker { image 'node:14-alpine' }
    }
    stages {
            stage('Test') 
                          {
              
                       steps 
                         {
                           sh 'node --version'
                         }
                           }
    
     stage('install') {
      steps {
        sh 'npm install'
            }
    }
    
    
    
    }
}
