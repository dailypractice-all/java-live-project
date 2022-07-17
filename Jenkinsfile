pipeline {
  agent {label java agent}
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
