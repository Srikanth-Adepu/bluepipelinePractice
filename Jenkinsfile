pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh 'compile.....'
        sh 'mvn -f bluepipelinePractice/maven-samples/single-module/pom.xml compile -Dlicense.skip=true '
      }
    }

  }
}