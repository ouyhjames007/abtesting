pipeline {
  agent any
  stages {
    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            echo 'aaaa'
          }
        }
        stage('test2') {
          steps {
            echo 'bbbb'
          }
        }
      }
    }
    stage('End') {
      steps {
        echo 'end'
      }
    }
  }
}