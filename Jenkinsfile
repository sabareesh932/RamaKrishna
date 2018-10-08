pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/sabareesh932/RamaKrishna.git', branch: 'master', credentialsId: '132p5a0211', poll: true)
      }
    }
  }
}