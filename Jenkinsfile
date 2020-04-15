pipeline {
   agent any
   stages {
       stage('A') {
           steps {
              withCredentials([[ $class: 'AmazonWebServicesCredentialsBinding',
                   credentialsId: 252527887968,                                  
                   accessKeyVariable: 'AWS_ACCESS_KEY',
                   secretKeyVariable: 'AWS_SECRET_KEY'
                                     ]]) { echo "asasdas" }
           }
       }
   }

}
