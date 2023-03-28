

pipeline{
	agent any

	tools{
	maven 'MAVEN'
	jdk 'oracleJDK'
	}

	stages{

	stage('build code'){
	steps{
	sh 'mvn clean install'
	}
	}
	
	}
}
