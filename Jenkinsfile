pipeline {
  agent any 
  stages {
    stage('test') {
      steps {
        sh 'rubocop'
	sh 'rspec'
        }
      }
    }
  }

