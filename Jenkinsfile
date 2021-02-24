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
        sh ' chown -R 126:133 "/.npm"'
         sh 'npm install'
            }
            }
    
     
    
    
    
    }
}
