pipeline {
  agent any
  stages {
    stage('Get The Code') {
      steps {
        echo 'Connecting Git Repository to Get the Code'
      }
    }

    stage('Run Unit Tests') {
      steps {
        echo 'Running Unit Tests'
      }
    }

    stage('Build The Code') {
      steps {
        echo 'Building Code'
      }
    }

    stage('UI Test') {
      steps {
        echo 'Running Selenium UI Tests'
      }
    }

    stage('Dockerize') {
      steps {
        echo 'Running Docker Compose'
        echo 'Saving Artifacts to Private Docker Hub'
      }
    }

    stage('Deploy The Server') {
      steps {
        echo 'Create a server on Portainer'
      }
    }

    stage('Load Test') {
      steps {
        echo 'Run JMeter Load Test'
        echo 'Send Result To the Team'
      }
    }

  }
}