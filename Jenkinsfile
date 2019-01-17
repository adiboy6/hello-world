pipeline {
  agent {
    node {
      label 'hello'
    }

  }
  stages {
    stage('first') {
      steps {
        echo 'hi'
      }
    }
    stage('two') {
      steps {
        sh 'ls'
      }
    }
  }
}