pipeline {
  agent any
  triggers {
    githubPush()
  }  
  stages {
    stage('echo') {
      steps {
       echo 'hello from the trigger2'
      }
    }

  }
}
