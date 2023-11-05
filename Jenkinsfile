pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "hello"'
      }
    }

    stage('test') {
      steps {
        retry(count: 2) {
          echo 'hey jenkins'
          sh 'echo \'complted\''
        }

      }
    }

  }
}