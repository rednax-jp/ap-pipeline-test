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
        echo 'checking host details'
        sh "hostname"
        sh "ls -ltr /"
      }
    }
  }
}
