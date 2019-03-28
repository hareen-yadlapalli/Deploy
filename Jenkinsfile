pipeline {
  agent any
  stages {
    stage('Run SQL in DEV') {
      steps {
        echo 'Executing SQL in DEV'
      }
    }
    stage('Deploy to DEV') {
      steps {
        echo 'Deploying build to DEV'
      }
    }
    stage('Restart DEV') {
      steps {
        echo 'Restarting DEV Apps'
      }
    }
    stage('Run SQL in SYS') {
      steps {
        echo 'Executing SQL in SYS'
      }
    }
    stage('Deploy to SYS') {
      steps {
        echo 'Deploying build to SYS'
      }
    }
    stage('Retart SYS') {
      steps {
        echo 'Restarting SYS Apps'
      }
    }
  }
}