pipeline {
  agent { any }
  stages {

    stage ("run our python) {
        script {
          sh "python add.py"
    }

    stage ("run test) {
      script {
        sh "pytest"
      }
    }
}
