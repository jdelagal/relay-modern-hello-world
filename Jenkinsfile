pipeline {
  agent {
    docker {
      image 'node'
      args '-p 3000:3000'
    }
    
  }
  stages {
    stage('') {
      steps {
        sh 'npm install'
      }
    }
  }
}