pipeline {
  agent any
  stages {
    stage('check-version') {
      steps {
        echo "testing"
        sh "uname -a"
        sh 'uname -v'
        sh "uname --h"
        sh 'which docker'
      }
    }
  stage('test-kubectl') {
    steps {
        echo 'checking kubernetes and helm'
        sh "which kubeclt"
        sh "which helm"
      }
    }
  }
}