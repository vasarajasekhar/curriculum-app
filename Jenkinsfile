pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/vasarajasekhar/curriculum-app', branch: 'dev')
      }
    }

    stage('Log') {
      steps {
        sh 'ls -la'
      }
    }

  }
}