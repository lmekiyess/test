pipeline {
  agent any
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
