pipeline {
    agent any
    stages {
      stage('Build') {
        steps {
          sh 'poetry install'
        }
      }
      stage('Test') {
        steps {
          sh 'poetry install'
          sh 'poetry run pytest -v -s tests'
        }
      }
    }
}