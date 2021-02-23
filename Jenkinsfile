pipeline 
{
agent any
  stages {
          stage (''Execute CI pipeline'') 
               {
                   agent {
                   docker { image 'node:12-buster-slim' }
                         }   
               }
            
  
          stage("build")
              {
                 steps
                 {
                    sh 'npm install'
                 }
             
              }
}
}
