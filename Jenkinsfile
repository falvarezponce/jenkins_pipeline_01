pipeline {
    agent any
	tools {
        maven 'apache-maven-3.6.3' 
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