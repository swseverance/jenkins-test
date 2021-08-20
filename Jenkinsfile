pipeline {
  agent any
  tools {nodejs "NodeJS 16.7.0"}
  stages {
    stage('Install') {
      steps {
        sh 'npm install'
      }
    }
    stage('Test') {
      steps {
        sh 'npm test --watch=false'
      }
    }
    stage('Build') {
      steps {
        sh 'npm run build'
      }
    }
  }
}
