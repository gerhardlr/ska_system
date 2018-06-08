pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'su jenkins'
        sh 'git submodule update --init --recursive --remote'
      }
    }
  }
}