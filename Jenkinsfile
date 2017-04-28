pipeline {
  agent {
    docker {
      image 'maven:3.3.9-jdk8'
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