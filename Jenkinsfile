pipeline {
	agent any
	stages {
		stage('Clone Repo'){
			steps{
			sh 'git fetch https://github.com/RWright1992/miniProjectMonitors.git'
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
