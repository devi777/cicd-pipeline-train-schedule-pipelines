pipeline {
  agent any
  stages {
    stage ('Build'){
      steps{
        echo 'Running build automation'
        sh   './gradlew build --no-daemon'
        archiveArchifacts artifacts:'dist/trainSchedule.zip'
      }
    } 
  }
}

