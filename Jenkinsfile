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
        mail bcc: '', body: 'Hello this is a test email', cc: '', from: '', replyTo: '', subject: 'Test', to: 'charan07c@gmail.com'
      }
    }

  }

 post {
   always {
    echo "sending email"
   }
 }

}

@Library('roboshop')_

pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        script {
          def abc = "Hello"
          def xyz = 10

          print "abc = ${abc}"
          print "xyz = ${xyz}"

          print abc

        }

      }
    }
  }

}

