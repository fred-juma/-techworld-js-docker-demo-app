pipeline {
  agent any
  stages {
    stage("build") {
      steps {
        echo 'Building the application'
      }
    }
    stage("test") {
      steps {
        echo 'Testing the application'
        echo 'Security Scan Done'
        echo 'QA approved'
      }
    }
    stage("deploy") {
      steps {
        echo 'Deploying the application'
      }
    }
  }
}
