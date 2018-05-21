pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'mhart/alpine-node:6'
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