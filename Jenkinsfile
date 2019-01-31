pipeline {
  agent {
    node {
      label 'ttn'
    }

  }
  stages {
    stage('Source') {
      steps {
        sh 'echo hello'
      }
    }
  }
  environment {
    COMPLETED_MSG = 'Build Done !'
  }
}