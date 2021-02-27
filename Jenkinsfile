pipeline {
  agent any
  stages {
    stage('input') {
      agent any
      steps {
        echo "test is hard ${test}"
      }
    }

    stage('') {
      steps {
        cleanWs()
      }
    }

  }
  environment {
    test = 'testtttt'
  }
}