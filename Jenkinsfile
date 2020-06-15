pipeline {
 agent any
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
  }
}
