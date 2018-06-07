pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('compile ') {
      steps {
        echo "Compilation started by ${MY_NAME}"
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
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
    TEST_USER = credentials('test-user')
  }
}