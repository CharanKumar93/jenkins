pipeline {

  agent {
    label 'ansible'
  }

  stages {

    stage('Hello') {
      steps {
        echo 'Hello World'
      }
    }

  }

 post {
   always {
    echo "sending email"
   }

   changed {
     echo "Blah blah blah"
   }

 }

}
