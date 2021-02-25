pipeline {
  agent any
  stages {
    stage('Git Check Out') {
      steps {
        git(url: 'https://github.com/rchidana/Accenture_Pipeline.git', branch: 'master')
      }
    }

    stage('Build') {
      steps {
        bat 'Compile.bat'
      }
    }

    stage('Completed') {
      steps {
        echo 'All is Well!!!'
      }
    }

  }
}