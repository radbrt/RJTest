pipeline {
  agent any
    stages {
      stage('Build') {
        steps {
          sh "R CMD build ."
        }
      }
      stage('Check') {
        steps {
          sh "R CMD check ."
        }
      }
    }
}
