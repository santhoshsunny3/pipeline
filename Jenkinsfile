pipeline {
  agent any
  stages {
     stage('compile') {
      steps {
        env.PATH = "${mvnHome}/bin:${env.PATH}"{
          sh 'mvn -B clean verify'
        }
      }
    }
  }
}
