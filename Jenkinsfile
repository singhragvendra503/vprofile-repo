pipeline{
  agent none
  stages{
    stage('Build'){
    agent {
    label "MAVEN"
      }
    
    steps {
    sh 'sudo cp -r * /var/www/html'
    }
    
    }
  }

}
