pipeline {
  agent any 
    stages {
      stage('one') {
        steps {
          echo 'Hi, this is Ayesha.'
        }
      }
      stage('two') {
        steps {
          input('Do you want to proceed')
        }
      }
      stage('three') {
        steps {
          mail bcc: '', body: 'hello', cc: '', from: '', replyTo: '', subject: 'hi', to: 'gitpractice03@gmail.com'
        }
      }
    }
}
