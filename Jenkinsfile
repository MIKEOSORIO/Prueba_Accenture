pipeline{
  agent any
  stages {
    stage('Build'){
      steps{
      echo "Do something"
      }
    }
    stage('Test'){
      steps{
       sh '''
        echo 'Do something'
        hostname
        echo 'hola'
        pwd
        '''
      }
    }
    stage('Deploy'){
      steps{
        echo "Do something2"
      }
    }
  }
}
