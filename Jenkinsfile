pipeline {
  agent {
    docker {
      image 'node:18'
    }
  }
  stages {
    stage('Verify Docker') {
      steps {
        sh 'node -v'
        sh 'npm -v'
      }
    }
  }
}
