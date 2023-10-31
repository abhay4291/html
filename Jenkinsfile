pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        script {
          // Check out the source code
          checkout scm
          // Print a message to the console
          echo 'Source code checkout completed'
        }
      }
    }
  }
}
