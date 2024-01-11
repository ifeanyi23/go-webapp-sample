pipeline {
  agent any
  tools {
    go '1.19'
  }
  environment {
        GO111MODULE='on'
  }
  stages {
    stage('dev') {
      steps {
        sh 'go test ./...'
      }
    }

  }  
}
