pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh './mvnw clean'
      }
    }

    stage('Test') {
      steps {
        sh './mvnw test'
      }
    }

    stage('Deploy') {
      steps {
        sh './mvnw package'
      }
    }

  }
}