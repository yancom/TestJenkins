pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        script{
          echo 'Building2'
          sh 'ls'
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
