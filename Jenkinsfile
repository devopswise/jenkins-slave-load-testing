pipeline {
  agent {
    label 'jenkins-k8s-slave' 
  }

  stages {
    stage('Install chromedriver') {
        steps {
          sh 'python loadtest.py'
        }
    }
}
