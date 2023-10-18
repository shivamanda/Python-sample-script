pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('Dev-123 code') {
      steps {
        sh 'python3 hello.py'
      }
    }
  }
}
