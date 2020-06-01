pipeline {
	agent any
     
	stages {
		stage('Stage 1 : Check Python Installed or not -- Pre-requestic') {
			steps {

				bat 'echo "Check Python Version"'
				bat 'python --version'
				bat 'echo "Python latest version is installed, up and running"'
                           
            }
        }
       
		stage('Stage 3 : Run the Appliation') {
			steps {
				bat 'echo "Lets trigger the application"'
				bat 'Hello.py'
				bat 'echo "Application Run Successful"'
			}
		}
      
    }
}
