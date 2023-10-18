pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('QA code') {
      steps {
        sh 'python3 hello.py'
      }
    }
  }
}
