pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'alpine'
    }

  }
  stages {
    stage(' Build') {
      steps {
        sh 'npn install'
      }
    }
  }
}