pipeline {
  agent any
  stages {
    stage('Install') {
      steps {
        sh 'npm install'
      }
    }
    stage('Build') {
      steps {
        sh 'npm run build'
      }
    }
    stage('Test') {
      steps {
        echo 'Esto es una prueba'
      }
    }
    stage('Test2') {
      steps {
        sh 'npm run test'
        sh 'npm run test'
      }
    }
  }
}