pipeline {
  agent {
    label('javaagent')
  }
  options {
    ansiColor('xterm')
  }
  stages {
    stage ('Build Project') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}
