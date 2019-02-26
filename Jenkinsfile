pipeline {
  agent any
  stages {
     stage('compile') {
      steps {
        build(job: 'compile', quietPeriod: -5)
      }
    }
  }
}
