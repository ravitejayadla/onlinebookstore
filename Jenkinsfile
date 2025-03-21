pipeline {  
    agent any  
        stages {  
       	    stage("git_checkout") {  
           	    steps {  
              	    echo "cloning repository" 
              	    echo "repo cloned successfully"  
              	    }  
         	    } 
            stage("maven life cycle"){
              steps{
                  sh 'mvn clean install'
              }
            }
        }
}
