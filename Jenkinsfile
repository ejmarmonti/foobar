pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('Stage1') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}