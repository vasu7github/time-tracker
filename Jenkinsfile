pipeline {
 agent any
 environment{
 PATH = "C:\DevTools\apache-maven-3.6.3:$PATH"
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
