pipeline {
   agent any
   
   stages {
     stages('package stage'){
      steps{
        withMaven(maven : '3'){
           sh 'mvn clean package'
        }
      }
     }
   }

}
