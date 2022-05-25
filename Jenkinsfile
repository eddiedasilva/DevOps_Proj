#!/usr/bin/env groovy
pipeline {
  agent any
  stages {
    stage('Docker Build') {
      agent any
      steps {
        sh 'docker run -it -d --network host --name testwebpag httpd'
      }
    }
  }
}
