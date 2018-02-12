pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building docker image'
        sh '/usr/local/bin/docker build . -t docker-ci-cd:1'
      }
    }
    stage('Test') {
      steps {
        echo 'testing docker image'
      }
    }
    stage('Publish') {
      steps {
        echo 'Ready to publish'
      }
    }
  }
}
