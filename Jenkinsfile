pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        script{
          echo 'Building'
          sh ls -la
        }
      }
    }

    stage('Test') {
      steps {
        echo 'Testing'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

  }
}
