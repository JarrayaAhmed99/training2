pipeline {
agent 
  {
  docker {
            image 'node:6-alpine' 
            args '-p 3000:3000' 
        }
  
  
  }
  stages {
  
       stage("build")
         {
              steps
                 {
                    echo "building done"
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
