pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deployment  done") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
