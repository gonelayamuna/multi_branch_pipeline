pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
               sh """
               echo "Building Artifact from Devlopment branch"
               """
           }
       }
      stage('Deploy Code') {
          steps {
               sh """
               echo "Deploying Code from Development branch"
               """
          }
      }
   }
}
