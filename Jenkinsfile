pipleline{
	agent any 
		stages{
			stage('Build'){
				steps{
					sh 'mvn clean package'
				}
      stage('Display'){
         sh 'ls -lrt target/'
      }
			}
		}
}
