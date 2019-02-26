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
    stage('Test') {
      steps {
        withMaven(maven : 'maven_3_6_0') {
          sh 'mvn Test'
        } 
      }
    }
    stage('Deployment stage') {
      steps {
       withMaven(maven : 'maven_3_6_0') {
          sh 'mvn deploy'
        }
      }
    }
  }
}
