pipeline {
	agent any
     
	stages {
		stage('Stage 1 : Check Python Installed or not -- Pre-requestic') {
			steps {
				bat 'echo "Check Python Version"'
				bat 'cd C:\\Users\\Dell\\AppData\\Local\\Programs\\Python\\Python38'
				bat 'python --version'
				bat 'echo "Python latest version is installed, up and running"'
                           
            }
        }
      
		stage('Stage 2 : Pull/Clone the Master code repository from SCM') {
			steps {
				bat 'echo "Clone the master branch into the repository"'
				bat 'cd C:\\Users\\Dell\\Documents\\Gopi\\Study\\Devops'
				bat 'git init'
				bat 'git clone https://github.com/GOPISGN/HelloWorld.git'
				bat 'echo "Clonning Successful"'
            }
        }
		 
		stage('Stage 3 : Run the Appliation') {
			steps {
				bat 'cd HelloWorld'
				bat 'pwd'
				bat 'echo "Lets trigger the application"'
				bat 'Hello.py'
				bat 'echo "Application Run Successful"'
			}
		}
      
    }
}
