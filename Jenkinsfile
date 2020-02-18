pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('test') {
      steps {
        sh 'echo "hello world"'
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