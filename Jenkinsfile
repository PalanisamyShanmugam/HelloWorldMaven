pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven 'mymaven'
        jdk 'myjava'
    }
	stages {
        stage('Compile') {
            steps {
               
                sh 'mvn compile' 
            }
        }
    }
}