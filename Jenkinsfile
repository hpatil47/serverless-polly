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
				                    sh 'serverless remove --stage dev --region ap-south-1'					
			                  }
		            }				
	      }		 	
}
