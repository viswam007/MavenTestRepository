pipeline{
  agent any
    stages {
       stage ('Compile stage')

         steps {
                 sh 'mvn clean compile'
             }
          }
   }

    stages {
       stage ('Testing stage')
         steps {
            sh 'mvn test'
             }
    }

    stages {
       stage ('Deployment stage')
         steps {
            sh 'mvn deploy'
             }
    }
