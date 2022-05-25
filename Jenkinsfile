#!/usr/bin/env groovy
pipeline {
    agent { dockerfile {True  } }
    stages {
        stage('build') {
          steps {
                sh 'echo "building"'
            }
        }
        stage('test') {
          steps {
                sh '
                   git --version
                   curl --version
                   node --version
                '
            }
        }

   }
}
