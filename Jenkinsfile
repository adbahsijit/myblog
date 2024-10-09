pipeline {
  agent any
  stages{
    stage('checkout code'){
      steps {
        git branch: 'main', url: "$(env.GIT_REPO_URL)"
      }
    }
  }
}
