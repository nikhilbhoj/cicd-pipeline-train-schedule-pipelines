pipeline {
  agent any 
  stages {
    stage ('Build') {
      steps {
        echo 'Running Build automation'
        sh './gradlew build  --no-daemon'
        archiveArtifacts artifcats: 'dist/trainSchedule.zip' 
      }
     }
   }
 }
