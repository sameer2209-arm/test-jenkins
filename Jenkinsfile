pipeline {
  agent {
    label 'oulu-lab'
  }
  stages {
    stage('Check branch'){
      steps{
        sh "echo ${BRANCH_NAME}"
      }
    }
  }
}
