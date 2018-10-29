pipeline {
  agent {
    docker {
      image 'jenkins-slave'
    }

  }
  stages {
    stage('Print to test') {
      steps {
        echo 'This is one more testing'
      }
    }
  }
}