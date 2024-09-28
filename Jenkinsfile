pipeline {
  agent {
    node {
      label 'jenkins-docker-slave'
    }

  }
  stages {
    stage('checkout-code') {
      steps {
        sh 'echo "hello world 2"'
      }
    }

    stage('build') {
      steps {
        sh 'echo "build"'
      }
    }

  }
}