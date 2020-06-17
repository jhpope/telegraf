pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git 'https://github.com/jhpope/telegraf.git'
        tool 'Go'
        sh 'make --version'
      }
    }

  }
}