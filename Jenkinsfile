pipeline {
  agent any
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

        stage('') {
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