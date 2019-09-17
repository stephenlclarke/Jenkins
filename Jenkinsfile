pipeline {
  agent any
  stages {
    stage('Prepare') {
      parallel {
        stage('Prepare') {
          steps {
            echo 'Prepare'
          }
        }
        stage('Build') {
          steps {
            echo 'Build'
          }
        }
        stage('Test') {
          steps {
            echo 'Test'
          }
        }
        stage('Publish') {
          steps {
            echo 'Publish'
          }
        }
      }
    }
  }
}