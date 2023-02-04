pipeline {
  agent any
    stages {
      stage(‘Build’) {
          steps {
               sh "C:/Program Files/apache-maven-3.8.6/mvn clean package"
               }
       }
      stage(‘Test’) {
         steps {
               sh "C:/Program Files/apache-maven-3.8.6/bin/mvn test"
          }
      }
  }
}
