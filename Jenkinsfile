pipeline {
	      agent any	 
	
	      stages {
               stage('Build') {
                        steps {
                            sh 'env'
                        }
                }
		            stage('Unit test') {
			                  steps {				
 			                      sh 'serverless --version' // to ensure it is installed
			                  }
		            }			
		
		            stage('Integration test') {
			                  steps {
				                    sh 'serverless deploy --stage dev --region ap-south-1'					
			                  }
		            }				
	      }	
}	 	
