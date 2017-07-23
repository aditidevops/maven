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
  }
}