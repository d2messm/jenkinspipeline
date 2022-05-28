pipeline {
  agent any 
  tools {
    maven 'maven1'
  }
  stages {
    stage('Compile') {
      steps {
        sh "mvn compile"
      }
    }
    stage('Unit test') {
      steps {
        sh "mvn test"
      }
    }
  }
}
