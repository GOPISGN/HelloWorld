pipeline {
   agent any
     
   stages {
      stage('Pre-Requistic') {
         steps {
            script {
               bat 'echo "Check python version"'
               bat 'set python_version = python --version'
               set python_version
            }
         }
      }
   }
}
