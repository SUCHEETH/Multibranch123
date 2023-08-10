node('built-in') 
 {
 stage('Continuous Download') 
   {
    
     git branch: 'main', url: 'https://github.com/ankitnarula28/awsmaven.git'
 
     }   

stage('Continuous Build') 

{

sh 'mvn package'

}

}
