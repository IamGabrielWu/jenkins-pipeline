pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo stage 1'
          }
        }
        stage('stage2') {
          steps {
            sh 'echo stage 2'
          }
        }
        stage('stage 3') {
          steps {
            sh 'echo stage 3'
          }
        }
      }
    }
    stage('converge') {
      steps {
        sh 'echo converge'
      }
    }
    stage('end') {
      steps {
        sh 'echo end'
      }
    }
  }
}