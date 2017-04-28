pipeline {
  agent {
    docker {
      image 'maven'
    }
    
  }
  stages {
    stage('info') {
      steps {
        echo 'hallo jenkinsFile'
      }
    }
    stage('check version of Docker') {
      steps {
        echo 'check docker version'
        timestamps() {
          sh ' docker version'
        }
        
      }
    }
    stage('final') {
      steps {
        echo 'end of build'
      }
    }
  }
}