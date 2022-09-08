pipeline {
  agent {label 'built-in node'}
  options {
    buildDiscarder(logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr : '5', daysToKeepStr: '', numToKeepStr: '5'))
    disableConcurrentBuilds()
  }
  stages {
    stage('Hello') {
      steps {
        echo "hello"
      }
    }
  }
}