pipeline {
   agent any
   stages {
       stage('A') {
           steps {
              withCredentials([[ $class: 'AmazonWebServicesCredentialsBinding',
                   credentialsId : 'aws',                                                 
                   accessKeyVariable: 'AWS_ACCESS_KEY',
                   secretKeyVariable: 'AWS_SECRET_KEY'
                                     ]]) { echo "asasdas" }
           }
       }
   }

}
