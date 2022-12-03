pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        sh 'git clone https://github.com/fmoindjie/jenkins-helloworld.git'
      }
    }

    stage('build') {
      steps {
        sh 'javac Main.java'
      }
    }

    stage('Run') {
      steps {
        sh 'java Main'
      }
    }

  }
}