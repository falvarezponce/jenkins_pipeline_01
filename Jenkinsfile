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
            		bat 'set'         
                    bat 'mvn install'            	
        	}
        }		
    }
}