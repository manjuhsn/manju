pipeline {
  agent any
  stages {
    stage('Build stage') {
      parallel {
        stage('Build stage') {
          steps {
            echo 'Hi hello'
          }
        }
        stage('job run') {
          steps {
            echo 'Manju'
            build 'buildbmc1'
          }
        }
      }
    }
    stage('build stage') {
      steps {
        echo 'hello world'
      }
    }
  }
}