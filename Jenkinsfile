pipeline {
  agent any  
  options {
    buildDiscarder(logRotator(numToKeepStr: '5'))
  }
  


    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
