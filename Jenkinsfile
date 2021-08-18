pipeline {
	agent any
	stages {
		stage('Clone Repo'){
			steps{
			sh 'ls'
			}
		}
		stage('Build Jar'){
			steps{
			sh 'mvn clean package'
			}
		}
		stage('Run Jar'){
			steps{
			sh 'ls'
			}
		}

	}


}
