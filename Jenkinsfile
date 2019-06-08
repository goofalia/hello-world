pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        git(url: 'https://github.com/goofalia/hello-world.git', branch: 'master', changelog: true, credentialsId: 'googalia')
      }
    }
  }
}