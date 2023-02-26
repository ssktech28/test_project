pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python --version'
      }
    }
    stage('test_practice') {
      steps {
        bat 'python -m pip install -U pip'
        bat 'pip --version'
      }
    }
  }
}
