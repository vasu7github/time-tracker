pipeline {
 agent any
 tools{
    jdk 'JAVA_HOME'
    maven 'M2_HOME'
 }
 stages{
  stage(SCM){
   steps{
   git clone 'https://github.com/vasu7github/time-tracker.git'
   bat.echo "First Project"
   bat.echo "PATH=%PATH%"
   bat.echo "M2_HOME=%M2_HOME%" 
   }
   }
  }
}
