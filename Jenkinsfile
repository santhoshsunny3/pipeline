pipeline {
  agent any
  stages {
     stage('compile') {
      steps {
        withMaven(maven : 'maven_3_6_0') {
          sh 'mvn clean compile'
        }
      }
    }
  }
}
