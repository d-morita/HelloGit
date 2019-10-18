pipeline {
  agent any
  stages {
    stage('ls hello.py') {
      steps {
        sh 'ls ./hello.py'
        timestamps()
      }
    }
    stage('Run hello.py') {
      steps {
        sh 'python hello.py'
      }
    }
  }
}