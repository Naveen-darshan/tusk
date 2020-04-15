pipeline{
	agent any
		stages{
			
		 stage('compile'){
			steps{
			echo "Compiled SuccessFully...!"
			}
		}
		stage('s3Upload')
      		 {      
           steps {
               withAWS(region:'us-west-1',credentials:'AKIATVS6VYZQMLHT7QOE')\
               {
                   s3Upload(file:'Hello.java', bucket:'gituplaodedbucket', path:'Hello.java')
               }
       	    }
     	  }
		stage('junit'){
			steps{
			echo "Junits run successfully"
			}
		}
		stage('deploy'){
		steps{
			echo "deployed successfully"
			}
		}
	}
}
