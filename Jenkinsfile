pipeline {
  agent any
  stages {
    stage('checkout submodules') {
      steps {
        sh 'git submodule update --init --recursive --remote'
      }
    }
  }
}