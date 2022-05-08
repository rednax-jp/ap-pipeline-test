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
        echo 'checking kubernetes and helm'
        sh "kubectl version"
        sh "helm version"
      }
    }
  }
}