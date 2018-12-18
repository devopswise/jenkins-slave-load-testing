pipeline {
  agent {
    label 'jenkins-dind-ssh-slave' 
  }

  stages {
    stage('Install chromedriver') {
      steps {   
          sh 'python loadtest.py'
        }
    }
  }
}
