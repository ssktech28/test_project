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
        bat 'python -m pytest test_practice.py --html=result.html'
      }
    }
  }
}
