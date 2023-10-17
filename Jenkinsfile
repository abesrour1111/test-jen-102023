pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('network') {
      steps {
        sh 'sh "ifconfig"'
      }
    }

  }
}