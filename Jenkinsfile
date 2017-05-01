pipeline {
  agent {
    docker {
      image 'mfriedenhagen/docker-maven'
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
        echo 'print docker version'
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