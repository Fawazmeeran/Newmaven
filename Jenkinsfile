pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        sh 'echo "checkout"'
        git(url: 'https://github.com/Fawazmeeran/Newmaven.git', branch: 'master', poll: true)
      }
    }
    stage('Done') {
      steps {
        sh 'echo "checkout done"'
      }
    }
  }
}