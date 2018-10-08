pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/sabareesh932/hahah123.git', branch: 'master', poll: true)
      }
    }
    stage('output') {
      steps {
        echo 'completed 1st time'
      }
    }
  }
}