pipeline {
    agent any
    stages {
      stage('Build') {
        steps {
          sh 'echo Hello, world!'
        }
      }
      stage('Test') {
        steps {
          sh 'pip install pytest'
          sh 'pytest -v -s tests'
        }
      }
    }
}