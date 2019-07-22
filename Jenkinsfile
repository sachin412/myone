pipeline {
    agent any

    environment {
		secret = credentials('SECRET_TEXT')
	}
  
    stages {
        stage('Build') { 
            steps {
		sh 'echo "my first pipeline.."'
		sh '''
                echo "this is multistep pipeline"
		ls -lah
		'''
            }
        }
        
    }
}
