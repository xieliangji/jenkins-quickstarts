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
        sh 'ls -la /usr/lib/jvm/java-8-openjdk-amd64/'
        sh 'docker inspect maven'
      }
    }
  }
}
