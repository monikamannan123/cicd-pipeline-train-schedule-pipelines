pipeline{

agent any
  stage
  {
    stage ('Build'){
      steps
      {
        echo 'running build automation'
        sh './gradlew build' --no-daemon'
				archiveArtifcats artifacts: 'dist/trainSchedule.zip'
      }
      
  }
  
}
}
