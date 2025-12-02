pipeline {
  agent none
  tools{
    maven mvn
  }
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
  }
}
