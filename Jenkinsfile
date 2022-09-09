pipeline {
  agent any
  stages {
    stage('getting maven version ') {
      parallel {
        stage('getting maven version ') {
          steps {
            bat 'mvn --version'
          }
        }

        stage('running maven project') {
          steps {
            bat 'mvn clean test'
          }
        }

      }
    }

  }
}