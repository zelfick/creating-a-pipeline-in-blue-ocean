pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:14-alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
}