pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'sudo yum npm install -y' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy check application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
