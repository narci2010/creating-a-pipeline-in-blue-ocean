pipeline {
  agent {
    docker {
      image 'node:10-alpine'
      args '-p 3000:3000 -v /root:/root'
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