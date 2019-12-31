pipeline {
  agent any
  stages {
    stage('Init group') {
      parallel {
        stage('Init') {
          steps {
            echo 'Hello Init'
          }
        }

        stage('Init 2') {
          steps {
            echo 'Init 2'
          }
        }

      }
    }

    stage('wget') {
      steps {
        sh 'wget google.com'
      }
    }

  }
}