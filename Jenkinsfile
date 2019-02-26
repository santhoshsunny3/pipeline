pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        build(job: 'compile', quietPeriod: -5)
      }
    }
    stage('Test') {
      steps {
        build(job: 'Test', quietPeriod: -5)
      }
    }
    stage('package') {
      steps {
        build(job: 'package', quietPeriod: -5)
      }
    }
    }
}
