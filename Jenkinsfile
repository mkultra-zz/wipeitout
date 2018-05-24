pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/mkultra/wipeitout.git', branch: 'master', poll: true)
        sh 'echo \'Running shell\''
      }
    }
    stage('Run Tests') {
      steps {
        sh 'echo \'Test should be run here\''
      }
    }
  }
}