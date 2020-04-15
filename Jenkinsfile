pipeline{
	agent any
		stages{
		 stage('compile'){
			 withCredentials([[$class: 'AmazonWebServicesCredentialsBinding',
                                          accessKeyVariable: 'AKIATVS6VYZQCNYFYO5U',
                                          credentialsId: 'test',
                                          secretKeyVariable: '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']]) {
										  
										  echo "sucess"
                            
                        }
	}
		
	}
}
