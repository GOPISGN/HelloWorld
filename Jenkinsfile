pipeline {
   agent any

   stages {
      stage('Pre-Requistic') {
         steps {
            bat 'echo "Check python version"'
            python_version = bat 'python --version'
            
         }
      }
   }
}
