pipeline {
  agent {
    docker {
      image 'python:3.5'
    }

  }
  stages {
    stage('ls hello.py') {
      steps {
        sh 'ls ./hello.py'
      }
    }
    stage('Run hello.py') {
      steps {
        sh 'python hell.py'
      }
    }
  }
}