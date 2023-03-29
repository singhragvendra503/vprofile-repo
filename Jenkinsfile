pipeline{
  agent none
  stages{
    stage('Build'){
    agent {
    label "MAVEN"
      }
    
    steps {
    sudo cp -r * /var/www/html/main
    }
    
    }
  }

}
