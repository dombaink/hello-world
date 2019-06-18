pipeline {
  agent {
    docker {
      image 'centos'
      args 'docke ps -a'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'docker ps -a'
      }
    }
  }
}