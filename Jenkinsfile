pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('deploy 10.10.10.95') {
      agent {
        label "docker"
      }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

  }
}
