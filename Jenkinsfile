pipeline {
   agent any
     
   stages {
      stage('Pre-Requistic') {
         steps {
            script {
               bat 'echo "Check python version"'
               ECHO OFF
               IF NOT "%python --version%" == "Python 3.8.2"
               ECHO "PASS"
            }
         }
      }
   }
}
