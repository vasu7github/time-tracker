pipeline {
 agent any
 tools{
   jdk 'JAVA_HOME'
   maven 'MAVAN_HOME'
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
