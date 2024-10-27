pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('wildestpeople') {
      steps {
        sh 'node --version'
      }
    }
  }
}
