pipeline {
  agent any
  stages {
    stage('input') {
      agent any
      steps {
        echo "test is hard ${test}"
        archiveArtifacts 'user.properties'
      }
    }

    stage('error') {
      steps {
        cleanWs()
      }
    }

  }
  environment {
    test = 'testtttt'
  }
}