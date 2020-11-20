pipeline{
     agent any 
     
     stages{
       
             stage('clean')                                                
             {  steps{
                     bat 'mvn clean'
                     } 
             
             }
              
             
             stage('Install')
             {  steps{
                       bat 'mvn install'                                          
                     }                                                       
             
             }
             
                stage('Deploy')
             {  steps{
                       bat 'mvn deploy'
                     } 
             
             }
           
        
           
           
          
       }
 
}

