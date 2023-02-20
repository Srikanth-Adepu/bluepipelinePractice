pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        echo 'Compiling.......'
        sh 'mvn -f bluepipelinePractice/maven-samples/single-module/pom.xml compile '
      }
    }

  }
}