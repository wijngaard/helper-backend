pipeline {
  agent none
  stages {
    stage('info') {
      steps {
        echo 'hallo jenkinsFile'
      }
    }
    stage('check version of Docker') {
      steps {
        sh 'docker version'
      }
    }
    stage('final') {
      steps {
        echo 'end of build'
      }
    }
  }
}