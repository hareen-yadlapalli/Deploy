pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        build 'Job1'
      }
    }
  }
  parameters {
    string(name: 'FirstParam', defaultValue: 'First Parameter', description: 'Enter value for first parameter')
  }
}