pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'ls'
        sh 'npm -v'
        sh 'npm i'
        echo 'install success'
        sh 'npm run build'
        echo 'build success'
        sh 'npm start'
      }
    }

  }
}