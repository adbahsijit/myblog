pipeline {
  agent any
  stages{
    stage('Checkout code'){
      steps {
        sh 'git clone https://github.com/adbahsijit/myblog.git'
      }
    }
    stage('Static code analysis'){
      steps {
        sh 'sleep 2'
      }
    }
  }
}
