pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        parallel(
          "Stage1": {
            sh 'echo "Hello Aditi"'
            
          },
          "Stage2": {
            sh 'echo "Welcome to Jenkins"'
            
          }
        )
      }
    }
    stage('Stage3') {
      steps {
        sh 'echo "Hello Stage3"'
        sh 'echo " Hello 2nd Step of Stage3"'
      }
    }
  }
}