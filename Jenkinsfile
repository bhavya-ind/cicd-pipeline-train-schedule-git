pipeline {
 agent any
  stages {
   stage {'build'} {
    steps {
     echo 'Running build automation' 
     sh './gradle.build --no-deamon'
     archiveArtifacts artifacts: 'dist\trainschedule.zip'
   }
  }  
 }       
}
