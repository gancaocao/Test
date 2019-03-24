pipeline {
  agent any
  stages {
    stage('checkout') {
      agent any
      steps {
        powershell(script: 'mvn clean package', returnStatus: true, returnStdout: true)
      }
    }
  }
}