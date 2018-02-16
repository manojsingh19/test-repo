pipeline {
  agent any
  stages {
    stage('Git Checkout') {
      steps {
        build(job: 'checkout', quietPeriod: 2, wait: true)
      }
    }
  }
}