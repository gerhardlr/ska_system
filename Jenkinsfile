pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'git submodule update --init --recursive --remote'
      }
    }
  }
}