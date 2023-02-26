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
        bat 'python -m pytest --alluredir=allure-report/ test_practice.py'
      }
    }
  }
}
