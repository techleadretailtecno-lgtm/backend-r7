pipeline {
 agent any
 stages {
  stage('Build') {
   steps {
    sh 'docker build -t retailfactory/backend-r7:latest .'
   }
  }
  stage('Push') {
   steps {
    sh 'docker push retailfactory/backend-r7:latest'
   }
  }
 }
}
