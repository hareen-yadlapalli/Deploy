def ZIP_NODE
def CODE_VERSION
pipeline {
  agent any
  stages {
    stage('Initialize the variables') {
      steps {
        script{
                    CODE_VERSION="test"
                }
      }
    }
    stage('Deploy on Beanstalk'){
            steps{
                println "${CODE_VERSION}"
                //build job: 'abcdefgh-PHASER' , parameters: [[$class: 'StringParameterValue', name: 'vpc', value: ENV], [$class: 'StringParameterValue', name: 'ZIP_NODE', value: ZIP_NODE], [$class: 'StringParameterValue', name: 'CODE_VERSION', value: CODE_VERSION], [$class: 'StringParameterValue', name: 'APP_VERSION', value: BUILD_NUMBER], [$class: 'StringParameterValue', name: 'AWS_DEFAULT_REGION', value: AWS_DEFAULT_REGION], [$class: 'StringParameterValue', name: 'ParentJobName', value: JOB_NAME]]
            }
        }
  }
  parameters {
    choice(choices: ['dev'], description: 'Name of the environment', name: 'ENV')
  }
}
