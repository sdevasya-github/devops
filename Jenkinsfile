pipeline {
  agent any
  environment {
    Version = '1.0'
  }
  stages {
  stage('Test') {
      steps {
        script {
          echo 'Test phase'
        }
      }
    }
  stage('Build') {
      steps {
        script {
          echo 'Build phase'
        }
      }
    }
  stage('Deploy') {
      steps {
        script {
          echo 'Deploy phase'
        }
      }
    }    
  }
}
