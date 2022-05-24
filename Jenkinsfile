#!/usr/bin/env groovy
pipeline {
    agent { docker { image 'httpd' } }
    stages {
        stage('build') {
          steps {
                sh 'echo "building"'
                sh 'docker run -it -d --network host --name mytestpage httpd'
            }
        }
        stage('test') {
          steps {
                sh 'echo "testing"'
            }
        }
      
   }		
}
