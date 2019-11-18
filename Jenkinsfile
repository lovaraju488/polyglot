pipeline{
   agent any
   stages{
      stage('Compile stage'){
        steps{
           sh 'mvn clean compile'
        }
      }
      stage('Testing stage'){
        steps{
           sh 'mvn clean test'
        }
      }
      stage('package stage'){
        steps{
           sh 'mvn clean package'
        }
      }
     }
   }
