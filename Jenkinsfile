pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('compile ') {
      steps {
        echo 'Compilation started..'
      }
    }
    stage('dosomething ') {
      steps {
        sh 'java -version '
      }
    }
  }
}