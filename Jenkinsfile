

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
        stage('build docker image'){
        steps{
        sh 'docker build -t webImage .'
        }
        }
	
	
}
}
