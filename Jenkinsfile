pipeline {
  agent any
  stages {
    stage("run test"){
      steps{
        script {
          sh "pytest test_add.py"
        }
      }
    }
  }
}
