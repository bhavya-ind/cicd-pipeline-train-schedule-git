pipeline {
 agent any
  stages {
   stage ('build') {
    steps {
     echo 'Running build automation' 
     sh 'npm install'
     sh 'rm package-lock.json'
     echo 'removed package-lock'
     echo 'done'
   }
  }  
 }       
}
