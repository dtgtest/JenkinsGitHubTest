#!groovy

pipeline{
 agent any
 options{
   timestamps()
 }
 environment{
 }
 stages{
   stage('Print Job Name'){
    steps{
     echo "Job Name is: ${env.JOB_NAME}... Thank you!"
    }
   }
 }
}
