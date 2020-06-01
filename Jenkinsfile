pipeline {
   agent any
   python_version {}
   stages {
      stage('Pre-Requistic') {
         steps {
            bat 'echo "Check python version"'
            python_version = bat 'python --version'
            
         }
      }
   }
}
