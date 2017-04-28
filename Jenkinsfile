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
        sh 'mvn --version'
      }
    }
  }
}