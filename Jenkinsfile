pipeline {
  agent any
  stages {
    stage('Start') {
      steps {
        mail(subject: 'Start', body: 'Start Pipeline', from: 'andre.shiraiwa@efi.com', to: 'andre.shiraiwa@efi.com')
        tool 'SonarQube Scanner 2.8'
      }
    }
  }
}