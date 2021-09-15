pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build 'maven'
      }
    }

  }
  environment {
    Dev = 'build'
  }
}