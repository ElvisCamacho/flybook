pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Building...'
      }
    }

    stage('Testing') {
      steps {
        echo 'Testing...'
      }
    }

    stage('SAST') {
      steps {
        echo 'scanning code'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

  }
}