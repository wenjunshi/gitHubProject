pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh '/data/maven3/apache-maven-3.1.1/bin/mvn clean install '
        sh '/data/maven3/apache-maven-3.1.1/bin/mvn clean install'
      }
    }
  }
}