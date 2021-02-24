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
       stage('permissions tarki7A') {
      steps {
        sh 'sudo chown -R 126:133 "/.npm"'
            }
      
    
     stage('install') {
      steps {
        sh 'npm install'
            }
    }
    
    
    
    }
}
