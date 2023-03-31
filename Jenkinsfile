pipeline{
  agent none
  stages{
    stage('Build'){
    agent {
    label "Firstnode"
      }
    
    steps {
    sudo cp -r * /var/www/html/main
    }
    
    }
  }

}
