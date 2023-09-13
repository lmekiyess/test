pipeline {
  agent { 
      docker { 
          image 'python:3-alpine' 
      } 
  } 
  stages {
    stage("run test"){
      steps{
        parallel(
        a: { sh "python -m pytest" },
        b: { sh "python -m pytest" } 
          )  
        }
      }
    }
  }
