pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'su jenkins'
        sh 'whoami'
        sh 'git fetch'
      }
    }
  }
}