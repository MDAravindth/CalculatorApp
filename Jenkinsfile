pipeline{
	agent any 
		stages{
			stage('Build'){
				steps{
					sh 'mvn clean package'
				}
			}	
      			stage('Display'){
				steps{
         				sh 'ls -lrt target/'
      				}	
			}
		}
}
