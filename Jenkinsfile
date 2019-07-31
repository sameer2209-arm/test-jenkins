pipeline {
  agent any
  stages {
    stage('Environment setup') {
      steps {
        sh 'apt install build-essential'
      }
    }
    stage('Build') {
      steps {
        sh 'g++ hello.cpp -o hello'
      }
    }
    stage('Run') {
      steps {
        sh './hello'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo Deploying....'
      }
    }
  }
}
