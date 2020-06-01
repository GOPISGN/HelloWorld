pipeline {
   agent any
     
   stages {
      stage('Pre-Requistic') {
         steps {
            script {
               bat 'echo "Check python version"'
               
               bat 'echo off'
               bat 'if "%python --version%" == "Python 3.8.2"' (
                  bat 'echo "Python version is latest"'
                  )
               
               
            }
         }
      }
   }
}
