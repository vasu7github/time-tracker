pipeline {
 agent any
 environment{
 MAVAN_HOME=C:\DevTools\apache-maven-3.6.3
 }
 stages{
  stage("Welcome"){
   steps{
    echo "Welcome to Jenkins Declaration"
   }
  } 
  stage(SCM){
   steps{
   git 'https://github.com/vasu7github/time-tracker.git' 
   }
   }
  stage("MAVEN-BUILD"){
   steps{
    sh "mvn clean package"
  }
}
