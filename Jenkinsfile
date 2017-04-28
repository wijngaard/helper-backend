pipeline {
  agent {
    dockerfile {
      filename 'witchDockerFile'
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