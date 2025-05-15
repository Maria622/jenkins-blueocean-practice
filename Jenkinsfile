pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        echo 'COmpiling'
        sh 'date'
      }
    }

    stage('Testing') {
      steps {
        echo 'testeando'
      }
    }

    stage('deploy') {
      steps {
        echo 'deployingg'
      }
    }

  }
  environment {
    AUTHOR = 'Camila'
  }
}