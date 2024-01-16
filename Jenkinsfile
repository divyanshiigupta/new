pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
         sh 'docker run -dit --name my-apache-app -p 3306:80 -v "$PWD":/usr/local/apache2/htdocs/ httpd:2.4
'
      }
    }
  }
}
