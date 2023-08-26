pipeline {
  agent any
  stages {
    stage('fetch code') {
      steps {
        git(url: 'https://github.com/ravi-shiva/GitHubDemo.git', branch: 'main')
      }
    }

    stage('install apache2') {
      steps {
        sh '''sudo apt update
sudo apt install apache2 -y
'''
      }
    }

  }
}