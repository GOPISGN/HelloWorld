pipeline {
   agent any
     
   stages {
      stage('Pre-Requistic') {
         steps {
            script {
               bat 'echo "Check python version"'
               bat 'ECHO OFF'
               bat 'IF NOT "%python --version%" == "Python 3.8.2"'
               bat 'ECHO "PASS"'
            }
         }
      }
   }
}
