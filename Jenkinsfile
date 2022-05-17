pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'ls -alF ll /opt/homebrew/Cellar/maven/3.8.5/libexec'
        sh 'mvn clean install'
      }
    }

  }
}
