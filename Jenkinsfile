pipeline {
  agent none
  stages {
    stage('test') {
      steps {
        sh 'ls -l'
      }
    }

    stage('dev') {
      steps {
        echo 'success'
      }
    }

  }
  environment {
    hello = 'w'
  }
}