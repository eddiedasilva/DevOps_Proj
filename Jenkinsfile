#!/usr/bin/env groov
// Declarative //
pipeline {
  agent any
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
  checkout scm
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
