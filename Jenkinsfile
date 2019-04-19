pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'testing'
      }
    }
    stage('stage') {
      steps {
        echo 'sleeping'
        sleep 30
      }
    }
    stage('prod') {
      steps {
        echo 'production'
      }
    }
  }
}