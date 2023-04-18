pipeline {
  agent any
  stages {
    stage('Lint') {
      steps {
        sh 'npm install'
        sh 'npm install eslint@7 --save-dev'
        sh 'npx eslint .'
      }
    }
  }
}
