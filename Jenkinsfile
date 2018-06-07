pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('compile ') {
      steps {
        echo 'Compilation started by ${MY_NAME}'
      }
    }
    stage('dosomething ') {
      steps {
        sh 'java -version '
      }
    }
  }
  environment {
    MY_NAME = 'TIBCO'
  }
}