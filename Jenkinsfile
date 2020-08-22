pipeline{
	agent any
	stages{
		stage('Ping remote'){
			steps{
				sh 'cat /var/lib/jenkins/secrets/initialAdminPassword'
			}
		}
		stage('display'){
			steps{
				sh 'ls -lrt'
			}
		}
	}
}
