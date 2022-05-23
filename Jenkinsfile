#pipeline {
#    agent { docker { image 'httpd' } }
#    stages {
#        stage('build') {
#          steps {
#                sh 'echo "testing"'
#            }
#        }
#      }
#   }
// Declarative //
pipeline {
 # agent any
  { docker { image 'httpd' } }
  stages {
  stage('Build') {
  steps {
  echo 'Building..'
  }
  }
  stage('Test') {
  steps {
  echo 'Testing..'
  }
  }
  stage('Deploy') {
  steps {
  echo 'Deploying....'
  }
  }
  }
}
// Script //
node {
  stage('Build') {
  echo 'Building....'
  }
  stage('Test') {
  echo 'Building....'
  }
  stage('Deploy') {
  echo 'Deploying....'
  }
}
