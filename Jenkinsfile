pipeline {
	      agent any	 

 	      stages {
               stage('Build') {
                        steps {
                            sh 'env'
                        }
                }		
 		            stage('Integration test') {
			                  steps {
				                    sh 'serverless deploy --stage dev --region ap-south-1'					
			                  }
		            }				
	      }		 	
}
