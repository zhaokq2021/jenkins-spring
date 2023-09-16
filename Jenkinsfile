pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'building'
      }
    }

    stage('Test') {
      steps {
        bat 'mvn test'
      }
    }

    stage('Deploy') {
      steps {
        bat 'mvn package'
      }
    }

  }
}