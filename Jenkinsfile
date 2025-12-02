@Library("my-shared-library") _
pipeline {
  agent none
  stages {
    stage ('build'){
      agent any
      steps{
          echo "hello Maroof siddiqui"
          sh 'mvn --version'
      }
    }
    stage ('deploy'){
      agent any
      steps{
          echo "Bye Maroof"
      }
    }
    stage('shared-library'){
      steps{
          helloWorld()
      }
    }
  }
}
