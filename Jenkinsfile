pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'sh mvn clean'
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