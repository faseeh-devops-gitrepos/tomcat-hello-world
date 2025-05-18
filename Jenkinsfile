pipeline {
	agent any
	stages {
		stage('Checkout') {
			steps {
				git 'https://github.com/faseeh-devops-gitrepos/tomcat-hello-world.git'
			}
		}
		stage('Deploy'){
			steps {
				sh 'cp web/index.jsp /mnt/c/Users/PC/Downloads/apache-tomcat-9.0.105-windows-x64/apache-tomcat-9.0.105/webapps/ROOT/'
				sh 'cp web/style.css /mnt/c/Users/PC/Downloads/apache-tomcat-9.0.105-windows-x64/apache-tomcat-9.0.105/webapps/ROOT/'
			}
		}
	}
}
