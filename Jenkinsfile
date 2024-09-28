pipeline {
  agent {
    node {
      label 'jenkins-docker-slave'
    }

  }
  stages {
    stage('checkout-code') {
      steps {
        sh 'echo "hello-world"'
      }
    }

    stage('test') {
      steps {
        sh 'echo "test2"'
      }
    }

  }
}