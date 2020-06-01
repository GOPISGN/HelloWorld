pipeline {
   agent any
   environment {}
  
   stages {
      stage('Pre-Requistic') {
         steps {
            script {
               bat 'echo "Check python version"'
               env.python_version = bat 'python --version'
               bat 'python_version'
            }
         }
      }
   }
}
