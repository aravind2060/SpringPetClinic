pipeline {
  agent any
  stages {
    stage('clean') {
      steps {
        sh 'sh \'mvnw clean\''
      }
    }

    stage('test') {
      steps {
        sh 'sh \'mvnw test\''
      }
    }

    stage('package') {
      steps {
        sh 'sh \'mvnw package\''
      }
    }

  }
}