pipeline {
  agent none
  stages {
    stage('oam') {
      steps {
        sh '''cd /home
git clone https://github.com/dablyo/test1.git
cd test1
go build -o main'''
      }
    }

  }
}