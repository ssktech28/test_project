pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('test_practice') {
      steps {
        sh 'pytest test_practice.py'
      }
    }
  }
}
