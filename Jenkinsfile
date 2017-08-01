pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        sh 'sh mvn clean install'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('QA') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}