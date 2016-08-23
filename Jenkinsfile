pipeline {
  image none
  stages {
    stage('build') {
      node('master') {
        echo 'looking'
        sh 'ls -lah'        
        checkout scm
        sh 'ls -lah'
      }
    }
  }
}
