#!/usr/bin/env groovy
pipeline {
  agent none
  stages {
    stage('Stage 1') {
      steps {
        script {
            sh "echo a"
        }
      }
    }
    stage('Stage 2') {
      steps {
        echo "a"
      }
    }
  }
}