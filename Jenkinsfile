pipeline {
  agent any
  stages {
    stage('Run SQL in DEV') {
      steps {
        sleep 2
      }
    }
    stage('Deploy to DEV') {
      steps {
        timeout(time: 2)
      }
    }
    stage('Restart DEV') {
      steps {
        timeout(time: 2)
      }
    }
    stage('Run SQL in SYS') {
      steps {
        timeout(time: 2)
      }
    }
    stage('Deploy to SYS') {
      steps {
        timeout(time: 2)
      }
    }
    stage('Start SYS') {
      steps {
        timeout(time: 2)
      }
    }
  }
}