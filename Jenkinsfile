#!/usr/bin/env groovy
pipeline {
  agent none
  stages {
    stage('Docker Build') {
      agent any
      steps {
        sh 'docker run -it -d --network host --name testwebpag httpd'
      }
    }
  }
}
