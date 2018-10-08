pipeline {
  agent none
  stages {
    stage('checkout') {
      parallel {
        stage('checkout') {
          steps {
            git(url: 'https://github.com/sabareesh932/Lakshmi143.git', branch: 'krishna', credentialsId: '132p5a0211', poll: true)
          }
        }
        stage('test') {
          steps {
            echo 'Hi this is for test.'
          }
        }
      }
    }
    stage('crack') {
      steps {
        dir(path: 'RamaKrishna') {
          sleep 10
        }

      }
    }
  }
}