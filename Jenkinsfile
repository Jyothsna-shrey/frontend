pipeline {
  agent {
    node {
      label 'Workstation'
    }
  }
  stages {
    stage('Docker build') {
      steps {
        sh 'docker build -t jyothsnashrey/d77-frontend .'
      }
    }

    stage('Docker Push') {
      steps {
        sh 'docker push jyothsnashrey/d77-frontend'
      }
    }

  }
}


// docker.io/