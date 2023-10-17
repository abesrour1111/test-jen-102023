pipeline {
  agent {
    node {
      label 'maître'
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