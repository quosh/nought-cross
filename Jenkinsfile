pipeline {
  agent any
  stages {
    stage('Stage 01') {
      parallel {
        stage('Step 01') {
          steps {
            sh 'echo "This is build $BUILD_NUMBER of demo $DEMO"'
          }
        }

        stage('Step 02') {
          steps {
            sh 'echo "Step 01"'
          }
        }

      }
    }

  }
  environment {
    DEMO = '1'
  }
}