pipeline {
  agent none
  stages {
    stage('Pull') {
      steps {
        sh 'git clone https://github.com/nirgeier/JenkinsLabs.git'
      }
    }

    stage('echo') {
      steps {
        sh 'echo "Does this work??" > blabla.txt'
      }
    }

  }
}