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
        withMaven(maven: 'maven386', globalMavenSettingsConfig: '28574bc2-3c5b-4350-9676-d25ab7fddca6'){
          sh "mvn clean deploy"
        }
      }
    }
 }
}
