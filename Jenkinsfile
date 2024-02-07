pipeline {
  agent any
  stages {
    stage('code') {
      steps {
        sh 'date'
      }
    }

    stage('build') {
      steps {
        sleep 10
        echo 'these is massage from build'
      }
    }

    stage('test') {
      steps {
        sh '''pwd
cal 2021'''
      }
    }

    stage('deploy') {
      steps {
        sleep 5
        echo 'msg from deploy'
      }
    }

  }
}