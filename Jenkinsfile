pipeline {
  agent {
    docker {
      image 'centos'
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