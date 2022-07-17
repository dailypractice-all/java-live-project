pipeline {
  agent any
  options {
    ansiColor('xterm')
  }
  stages {
    stage ('Create jobs') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}
