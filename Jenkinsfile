pipeline {
  agent {
    node {
      label 'node1'
    }

  }
  stages {
    stage('network') {
      steps {
        sh 'ifconfig'
      }
    }

  }
}