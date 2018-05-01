pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say hello') {
      steps {
        echo 'Hello ${MY_NAME}!'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Brian'
  }
}