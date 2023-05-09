pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/vasarajasekhar/curriculum-app', branch: 'dev')
      }
    }

    stage('Build Code') {
      steps {
        sh 'echo "skills"'
      }
    }

  }
}