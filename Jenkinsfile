#!groovy

pipeline{
 agent any
 options{
   timestamps()
 }
 stages{
   stage('Print Job Name'){
    steps{
     echo "Job Name is: ${env.JOB_NAME}... Thank you!"
    }
   }
 }
}
