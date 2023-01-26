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

    stage('Hello1') {
      steps {
        echo 'Hello World'
      }
    }

    stage('Hello2') {
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
