pipeline {
  agent any
  tools { go '1.19' }
  stages {
    stage('dev') {
      steps {
        sh 'go test ./...'
      }
    }

  }
}
