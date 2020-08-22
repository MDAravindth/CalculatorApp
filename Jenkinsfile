pipeline{
	agent any
	stages{
		stage('Ping remote'){
			steps{
				sh 'ansible webservers -m ping'
			}
		}
		stage('display'){
			steps{
				sh 'ls -lrt'
			}
		}
	}
}
