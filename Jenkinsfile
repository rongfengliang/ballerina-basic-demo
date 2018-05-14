pipeline {
  agent {
    node {
      label 'docker-65'
    }

  }
  stages {
    stage('ballerina build') {
      steps {
        sh 'ballerina build app.bal'
      }
    }
     stage('show files') {
      steps {
        sh 'ls -sialh'
      }
    }
  }
}
