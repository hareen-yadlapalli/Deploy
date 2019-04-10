pipeline {
  agent any
  stages {
    stage('Stage 1') {
      parallel {
        stage('Stage 1') {
          steps {
            build 'Job1'
          }
        }
        stage('Print') {
          steps {
            echo 'current build number: ${currentBuild.number}'
          }
        }
      }
    }
  }
  parameters {
    string(name: 'FirstParam', defaultValue: 'First Parameter', description: 'Enter value for first parameter')
  }
}