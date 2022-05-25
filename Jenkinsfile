#!/usr/bin/env groovy
pipeline {
    agent { docker { image 'httpd' } }
    stages {
        stage('build') {
          steps {
                sh 'echo "building"'
            }
        }
        stage('test') {
          steps {
                sh 'echo "testing"'
            }
        }
      
   }		
}
