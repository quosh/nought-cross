pipeline {
  agent any
  stages {
    stage('Step 01') {
      steps {
        sh 'echo "This is build $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}