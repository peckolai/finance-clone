pipeline {
  agent any 
  stages {
    stage('test') {
      steps {
	sh 'gem install bundler'
	sh 'bundle install'
        sh 'rubocop'
	sh 'rspec'
        }
      }
    }
  }

