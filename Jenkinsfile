pipeline {
    agent {
        docker { image 'python:3' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'pip --version'
            }
    stage('hello') {
      steps {
        sh 'python3 hello.py'
      }
    }
  }
}
