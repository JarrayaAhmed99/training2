pipeline 
{
agent any
  stages {
          stage ('Execute CI pipeline') 
               {
                   agent {
                   docker { image 'node:12-buster-slim' }
               }
            
  
          stage("build")
              {
                 steps
                 {
                    sh 'npm install'
                 }
               }
          stage("test")
             {
               steps
                 {
                    echo "testing done done"
                 }
              }
          stage("deploy")
             {
                  steps
                   {
                    echo "deploying done"
                   }
             }
         }

}
