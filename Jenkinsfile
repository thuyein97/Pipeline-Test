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
          stage('Three'){
               when {
                    not  {
                              branch "main"
                    }
               }
          steps {
                    echo "Hello"
         }
     }                                  
                                        
                                        
                                        
