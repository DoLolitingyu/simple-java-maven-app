pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "woshilaiwande"'
      }
    }
    stage('Test') {
      environment {
        CI = 'true'
      }
      steps {
        sh 'echo "aaaaaaaaa"'
      }
    }
  }
}