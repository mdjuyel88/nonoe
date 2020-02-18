pipeline {
  agent {
    node {
      label 'my_node_label'
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