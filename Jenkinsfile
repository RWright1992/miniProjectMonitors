pipeline {
	agent any
	stages {
		stage('Remove old Jar'){
                        steps{
                        sh 'if [ -d "target" ]; then rm -Rf target; fi'
                        }
                }

		stage('Build Jar'){
			steps{
			sh 'mvn clean package'
			}
		}
		stage('Run Jar'){
			steps{
			sh 'java -jar target/monitors-0.0.1-SNAPSHOT.jar &'
			}
		}

	}


}
