pipeline {
  agent any

  stages {
    stage("build") {
      steps {
        echo 'building the application...'
        echo 'Application built'
        nodejs('Nodejs') {
          sh 'npm install --modules-folder app'
        }
      }
    }
    stage("test") {
      steps {
        echo 'testing the application...'
      }
    }
    stage("deploy") {
      steps {
        echo 'deploying the application...'
      }
    }
  }
}