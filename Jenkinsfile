

                
     
    
					
    

  
  node {
     
    
    stage('git clone')
         git credentialsId: 'us', poll: false, url: 'https://github.com/rajiasthana/jenkins1.git'
        
    
    stage('maven version') {
        bat '''mvn --version'''
    }

    stage') ('maven clean') {
	    bat '''mvn clean'''
	 }
	
	 
    
    stage('maven validate') {
        bat '''mvn validate'''
    }
	stage('maven compile') {
         bat '''mvn compile'''   
        
    }
   
    stage('maven test') {
        bat '''mvn test'''
    }
	
	stage('maven package') {
         bat '''mvn package'''   
     }   
    
    stage('maven deploy') {
        bat '''mvn deploy'''
    }