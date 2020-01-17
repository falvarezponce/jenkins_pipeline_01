pipeline {
    agent any
	tools {
        maven 'MAVEN_CONF' 
    }   
     
    stages {
        stage ('Compile Stage Demo') {
            steps {                
                    bat 'mvn clean'            	
        	}
        }
        stage ('Install Stage Demo') {
            steps {  
            		bat 'env'              
                    bat 'mvn install'            	
        	}
        }		
    }
}