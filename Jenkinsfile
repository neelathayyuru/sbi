pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        sh '''git pull
'''
      }
    }
  }
  environment {
    node = 'test'
  }
}