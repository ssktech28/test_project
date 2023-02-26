pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python3 --version'
      }
    }
    stage('test_practice') {
      steps {
        bat 'pytest test_practice.py'
      }
    }
  }
}
