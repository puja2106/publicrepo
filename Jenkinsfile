pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
    stage('Test 2') {
      steps {
        echo "My first pipeline"
        echo "Github webhook added"
      }
    }
  }
}
