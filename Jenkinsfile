pipeline {
  agent {
    label 'jdk8'
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