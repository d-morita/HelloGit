pipeline {
  agent any
  stages {
    stage('ls hello.py') {
      steps {
        sh '''date
ls ./hello.py'''
      }
    }
    stage('Run hello.py') {
      steps {
        sh 'python hello.py'
      }
    }
  }
}