pipeline {
  agent {
    label 'oulu-lab'
  }
  stages {
    stage('Check branch'){
      steps{
        sh "echo ${env.BRANCH_NAME}"
      }
    }
  }
}
