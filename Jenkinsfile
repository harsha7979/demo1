pipeline {
  agent any
  stages{
    stage('test') {
      steps{
        echo "this is test"
      }
    }
    stage('clone') {
      steps{
        git branch: 'dev', url: 'https://github.com/harsha7979/demo1.git'
      }
    }
  }
}
