// Declarative //
pipeline {
 # agent any
  agent { docker { image 'httpd' } }
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
