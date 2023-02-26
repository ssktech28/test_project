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
        bat 'curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py'
      }
    }
  }
}
