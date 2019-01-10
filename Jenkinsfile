pipeline {
  agent {
    node {
      label 'onboard_test_node'
    }

  }
  stages {
    stage('verify') {
      steps {
        sh 'echo "Hello World"'
      }
    }
    stage('Build') {
      steps {
        sh 'echo "Build the application"'
      }
    }
  }
}