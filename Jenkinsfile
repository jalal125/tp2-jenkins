pipeline {
  agent any

  tools {
    maven 'Maven 3.9.10'
  }

  stages {
    stage('Build & Test') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}
