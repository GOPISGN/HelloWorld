pipeline {
   agent any
     
   stages {
      stage('Check Python Installed or not -- Pre-requestic') {
         steps {
            bat 'echo "Check Python Version"'
            python_version = bat 'python --version'
            bat 'echo %python_version%'
               
               
            }
         }
      }
   }
