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
			sh 'mvn clean install'
			}
		}
		stage('Run Jar'){
			steps{
			sh 'ls'
			}
		}

	}


}
