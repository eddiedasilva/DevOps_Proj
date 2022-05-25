#!/usr/bin/env groovy
pipeline {
    agent { dockerfile:true }
    stages {
        stage('build') {
          steps {
                sh 'echo "building"'
            }
        }
        stage('test') {
          steps {
                sh 'echo "testing"
                   node --version
                   git --version
                   curl --version
                '
            }
        }
      
   }		
}
