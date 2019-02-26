pipeline {
  agent any
  stages {
     stage('compile') {
      steps {
        build(job: 'mvn clean compile', quietPeriod: -5)
      }
    }
  }
}
