pipeline {
  agent any
  stages {
    stage('compile file') {
      steps {
        sh 'javac main.java'
      }
    }

    stage('run file') {
      steps {
        sh 'java main.java'
      }
    }

  }
}