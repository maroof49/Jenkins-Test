pipeline {
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
      post {
        echo "end"
      }
    }
  }
}
