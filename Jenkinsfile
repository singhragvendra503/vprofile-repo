pipeline{
  agent none
  stages{
    stage('Build'){
    agent {
    label "Firstnode"
      }
    
    steps {
    sh 'sudo cp -r * /var/www/html/main'
    }
    
    }
  }

}
