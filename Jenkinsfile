pipeline {
  agent any
  stages {
    stage('check-version') {
      steps {
        echo "testing"
        sh "docker version"
      }
    }
  stage('test-kubectl') {
    steps {
        sh "kubectl version"
      }
    }
  }
}