pipeline {
  agent { docker 'maven:3.3.3' }
  stages {
    stage('build') {
      steps {
        sh 'pwd'
        sh 'id'
        sh 'ps'
        sh 'mvn --version'
        sh 'echo "hello world" > hello.txt'
        sh 'ls -al'
      }
    }
  }
}
