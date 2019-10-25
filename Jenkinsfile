pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git 'https://github.com/AlanPu/jenkins_demo.git'
      }
    }
    stage('Deploy') {
        cp hello.html /var/www.html/.
    }
  }
}
