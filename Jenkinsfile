pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            echo 'This is stage1'
          }
        }
        stage('Stage 2') {
          steps {
            mail(subject: 'test mail', body: 'this is test mail from blue ocean stage 2', to: 'manoj.singh@sdgc.com')
          }
        }
      }
    }
  }
}