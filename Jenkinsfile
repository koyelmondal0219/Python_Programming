pipeline {
  agent any
  stages {
    stage('Create') {
      steps {
        echo 'I am created'
      }
    }

    stage('Test') {
      steps {
        echo 'I am tested!!!'
      }
    }

    stage('deploy') {
      steps {
        sh './mvnw clean compile'
      }
    }

  }
}