pipeline {
  agent any
  tools {
        nodejs 'nodejs'
        python3 'python3'
    }
  stages {
    stage('version') {
      steps {
        sh 'python --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python3 hello.py'
      }
    }
  }
}
