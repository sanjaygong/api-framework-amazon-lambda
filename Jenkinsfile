pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        withMaven(maven: 'M3') {
          sh 'mvn clean install'
        }

      }
    }
  }
}