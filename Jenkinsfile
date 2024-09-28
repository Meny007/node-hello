pipeline {
  agent {
    node {
      label 'jenkins-docker-slave'
    }

  }
  stages {
    stage('checkout-code') {
      steps {
        git(url: 'https://github.com/Meny007/node-hello.git', branch: 'master', changelog: true, poll: true)
      }
    }

    stage('build') {
      steps {
        sh 'echo "build"'
      }
    }

  }
}