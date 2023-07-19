pipeline {
    agent any
tools {
  maven 'mannn'
}

    stages {
        stage('clone the code') {
            steps {
            sh 'git clone https://github.com/Karisegowthami/hello-world-1.git'
            }
        }
         stage('build my code') {
            steps {
            sh 'maven package'
   }
}
