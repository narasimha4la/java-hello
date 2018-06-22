pipeline {
  agent any
  stages {
    stage('uat') {
      parallel {
        stage('uat') {
          steps {
            sh 'echo "UAT"'
          }
        }
        stage('dev') {
          steps {
            sh 'echo "you are at dev"'
          }
        }
      }
    }
    stage('prod') {
      steps {
        sh 'echo "you are at prod!! Be careful"'
      }
    }
  }
}