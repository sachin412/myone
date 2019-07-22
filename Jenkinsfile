pipeline {
    agent any

    environment {
		secret = credentials('SECRET_TEXT')
	}  
  
    stages {
        stage('Build') { 
            steps {
	  sh 'echo $secret'
		
                
            }
        }
        
    }
}
