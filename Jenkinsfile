pipeline {
  agent any {
  
  stages {
    stage ('build compile stage') {
      steps {
        withMaven (maven: 'maven-3') {
             bat 'start cmd.exe /c D:\\run.bat'
          
        }
        
      }
    }
    stage ('Testing stage') {
       steps {
        withMaven (maven: 'maven-3') {
          
           bat 'start cmd.exe /c D:\\test.bat'  
                  }
        
      }
         
         
       } 
    }
    
    
  }
    
    
 }                   
}
