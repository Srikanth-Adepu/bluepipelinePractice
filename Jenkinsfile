pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        echo 'cloning.......'
        sh 'git clone https://github.com/Srikanth-Adepu/bluepipelinePractice.git'
      }
    }

    stage('Compile') {
      steps {
        sh 'mvn -f bluepipelinePractice/maven-samples/single-module/pom.xml compile'
      }
    }

  }
}