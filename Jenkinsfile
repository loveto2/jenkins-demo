pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'npm install'
        echo 'install success'
        sh 'npm build'
        echo 'build success'
        sh 'npm start'
      }
    }

  }
}