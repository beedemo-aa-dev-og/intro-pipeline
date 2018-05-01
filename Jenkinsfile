pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say hello') {
      steps {
        echo 'Hello world!'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Brian'
  }
}