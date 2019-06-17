pipeline {
  agent {
    docker {
      image 'hello-world'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'docker ps'
      }
    }
  }
}