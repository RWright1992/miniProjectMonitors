pipeline {
	agent any
	stages {
		stage('Build Jar'){
			steps{
			sh 'mvn clean package'
			}
		}
		stage('Run Jar'){
			steps{
			java '-jar target/monitors-0.0.1-SNAPSHOT.jar &'
			}
		}

	}


}
