pipeline {
  agent any
  stages {
    stage('Prepare'){
      steps{
        script{
          echo 'About to send the email'
        }
      }
    }
    stages('Sending'){
           steps{
             script{
               echo 'About to send the email'
             }
           }
    }
    stages('Post'){
      steps{
        script{
          echo 'Email sent'
        }
      }
    }
  }
}
    
