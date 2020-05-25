pipeline{
    agent any
      triggers {
        githubPush()
      }
      stages {
        stage('Build') {
          steps{
            echo 'This is a build step'
          }
        }
        stage('Test') {
          steps{
            echo 'This is a test step'
            sleep(20)
          }
        }
        stage('Deploy') {
          steps{
            echo 'This is a deploy step'
        }
      }
    }
  }
