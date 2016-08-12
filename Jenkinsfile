pipeline {
  image docker:'node:0.12'
  stages {
    stage('build') {
      sh 'ls -lah'
      sh 'npm --version'
      sh 'npm install'
    }
    stage('test') {
      sh 'npm test'
    }
  }
}