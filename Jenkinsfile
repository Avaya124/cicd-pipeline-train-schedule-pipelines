pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        echo 'running build automation'
        sh './gradlew build' 
        archiveArtifacts artifacts: 'dist/train-schedule.zip'
        }
       }
       }
       }
