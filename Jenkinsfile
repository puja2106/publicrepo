pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('checkout') {
      steps {
        git credentialsId: 'c9018113-74d0-489b-a645-028032575992' url: 'https://github.com/puja2106/publicrepo.git
      }
    }
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
    stage('Test 2') {
      steps {
        echo "My first pipeline"
      }
    }
  }
}
