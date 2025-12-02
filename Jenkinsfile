@Library("my-shared-library") _
pipeline {
  agent none
  stages {
    stage ('build'){
      agent any
      steps{
          echo "hello Maroof siddiqui"
      }
    }
    stage ('deploy'){
      agent any
      steps{
          echo "Bye Maroof"
      }
    }
    stage('shared-library'){
      agent any
      steps{
          helloWorld()
      }
    }
  }
}
