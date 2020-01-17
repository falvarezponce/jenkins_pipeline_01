pipeline {
    agent any
	tools {
        maven 'MAVEN_CONF' 
    }   
     
    stages {
        stage ('Compile Stage Clean') {
            steps {                
                    bat 'mvn clean'            	
        	}
        }
        stage ('Compile Stage Test') {
            steps {                
                    bat 'mvn test'            	
        	}
        }        
        stage ('Install Stage Install') {
            steps {         
                    bat 'mvn install'            	
        	}
        }		
    }
}