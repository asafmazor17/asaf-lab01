pipeline {
  agent any
  stages {
    stage('Pull') {
      steps {
        sh '''git clone https://github.com/nirgeier/JenkinsLabs.git .
echo "Hello" > test.txt'''
      }
    }

  }
}