pipeline {
  agent {
    node {
      label 'centos-7.2'
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