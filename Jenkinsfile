pipeline {
  agent any
  tools {nodejs "NodeJS 16.7.0"}
  stages {
    stage('Test') {
      steps {
        sh 'npm test'
      }
    }
    stage('Build') {
      steps {
        sh 'npm run build'
      }
    }
  }
}
