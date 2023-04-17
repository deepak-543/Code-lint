pipeline {
  agent any
  stages {
    stage('Lint') {
      steps {
        sh 'npm install'
        sh 'npx eslint .'
      }
    }
  }
}
