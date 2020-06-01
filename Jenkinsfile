pipeline {
	agent any
     
	stages {
		stage('Stage 1 : Check Python Installed or not -- Pre-requestic') {
			steps {
				bat 'echo off'
				bat 'echo "Check Python Version"'
				bat 'python --version'
				bat 'echo "Python latest version is installed, up and running"'
				bat 'echo on'
                           
            }
        }
      
		stage('Stage 2 : Clone or Checkout the Master code repository from SCM') {
			steps {
				bat 'echo "Clone or checkout the master branch"'
				bat 'git init'
				bat 'git remote add origin https://github.com/GOPISGN/HelloWorld.git'
				bat 'git fetch'
				bat 'get checkout master'
				bat 'echo "Clonning Successful"'
            }
        }
		 
		stage('Stage 3 : Run the Appliation') {
			steps {
				bat 'echo "Lets trigger the application"'
				bat 'C:\Users\Dell\Documents\Gopi\Study\DevopsHello.py'
				bat 'echo "Application Run Successful"'
			}
		}
      
    }
}
