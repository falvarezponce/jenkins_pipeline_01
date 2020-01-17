pipeline {
    agent any
	tools {
        maven 'apache-maven-3.6.1' 
    }   
     
    stages {
        stage ('Compile Stage Demo') {
            steps {                
                    bat 'mvn clean'            	
        	}
        }
        stage ('Install Stage Demo') {
            steps {                
                    bat 'mvn install'            	
        	}
        }		
    }
}