pipeline {
     agent any
     stages {
         stage('stage one') {
              steps {
                 echo "Build stage is running"
              }
         }
         stage('ask stage') {
              steps {
                 input('Do you want to proceed')
              }
          }
          stage('stage three') {
               steps {
                  echo 'python --version'
              }
          }     
     }                                  
}                                        
                                        
                                        
