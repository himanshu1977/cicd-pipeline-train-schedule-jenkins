pipeline {
 agent any 
 stages {
  stage ('Build') {
  steps {
  echo 'Running build automation.this is a new build'
  sh './gradlew build --no-daemon' 
  archiveArtifacts artifacts: 'dist/trainSchedule.zip'
 }
}
}
}
 
 
 
