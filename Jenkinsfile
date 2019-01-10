pipeline {
  agent {
    node {
      label 'any'
    }

  }
  stages {
    stage('Verify') {
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
