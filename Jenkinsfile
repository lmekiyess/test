pipeline {
  agent any
  stages {
    stage("run test"){
      steps{
        script {
          sh "python -m pytest"
        }
      }
    }
  }
}
