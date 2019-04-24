pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        echo 'this is 1st step!'
      }
    }
    stage('step2') {
      steps {
        echo 'this is step 2'
        echo 'step 2-1'
        echo 'step 2-2'
      }
    }
    stage('end') {
      steps {
        echo 'this is end'
      }
    }
  }
}