pipeline {
  agent any
  stages {
    stage('check index page') {
      steps {
        sh 'cat index.html'
      }
    }
    stage('check css page') {
      steps {
        sh 'cat /css/style.css'
      }
    }
  }
}