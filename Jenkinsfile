pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('wildpeople') {
      steps {
        sh 'node --version'
      }
    }
  }
}
