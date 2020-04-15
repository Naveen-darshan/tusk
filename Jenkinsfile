pipeline {
   stages {
       stage('A') {
           steps {
              withCredentials([[ $class: 'AmazonWebServicesCredentialsBinding',
                   credentialsId : 'aws',                                                 
                   accessKeyVariable: 'AWS_ACCESS_KEY',
                   secretKeyVariable: 'AWS_SECRET_KEY'
                                     ]]) { }
           }
       }
       stage('B') {
           steps {
              withCredentials([[ $class: 'AmazonWebServicesCredentialsBinding',
                   credentialsId : 'aws',                                                 
                   accessKeyVariable: 'AWS_ACCESS_KEY',
                   secretKeyVariable: 'AWS_SECRET_KEY'
                                     ]]) { }
           }
       }
   }

}
