pipeline {
  agent any
  stages {
    stage('Git Checkout') {
      steps {
        build(job: 'checkout', quietPeriod: 2, wait: true)
        echo 'this is test job 1'
      }
    }
  }
}