pipeline {
  agent { 
      docker { 
          image 'python_with_pytest' 
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
