pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        sh 'go test ./...'
      }
    }

  }
  tools {
    go '1.19'
  }
}