pipeline {
    agent any
    stages {
        stage ('Compile Stage Demo') {

            steps {
                withMaven(maven : 'apache-maven-3.6.1') {
                    bat 'mvn clean compile'
                }
            }
        }
        stage ('Testing Stage Demo') {

            steps {
                withMaven(maven : 'apache-maven-3.6.1') {
                    bat 'mvn test'
                }
            }
        }
        stage ('Install Stage Demo') {
            steps {
                withMaven(maven : 'apache-maven-3.6.1') {
                    bat 'mvn install'
                }
            }
        }
    }
}
