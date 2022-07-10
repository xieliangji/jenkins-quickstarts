pipeline {
  agent { 
    docker {
      image 'maven:3.3.3' 
      args '--name maven'
    }
  }
  stages {
    stage('build') {
      steps {
        sh 'pwd'
        sh 'id'
        sh 'ps'
        sh 'mvn --version'
        sh 'echo "hello world" > hello.txt'
        sh 'ls -al'
        sh 'docker inspect maven'
      }
    }
  }
}
