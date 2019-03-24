pipeline {
  agent any
  stages {
    stage('checkout') {
      agent any
      steps {
        sh 'mvn clean package'
      }
    }
  }
}