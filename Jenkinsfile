pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        sh 'app = docker.build("adminturneddevops/go-webapp-sample")'
      }
    }

  }
}