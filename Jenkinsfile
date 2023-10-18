pipeline {
  agent {
    node {
      label 'node2'
    }

  }
  stages {
    stage('network') {
      parallel {
        stage('network') {
          steps {
            sh 'ifconfig'
          }
        }

        stage('stage2') {
          steps {
            sh 'cat /etc/passwd'
          }
        }

        stage('error') {
          steps {
            echo 'test'
          }
        }

      }
    }

    stage('stage3') {
      steps {
        sh 'cat /etc/group'
        echo 'fin'
      }
    }

  }
}