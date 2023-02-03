pipeline {
  agent any
    stages {
      stage('Build') {
          steps {
                bat'\Program Files\apache-maven-3.8.6\mvn clean package'
               }
       }
      stage('Test') {
         steps {
              bat'\Program Files\apache-maven-3.8.6\bin\mvn test'
          }
      }
  }
}
