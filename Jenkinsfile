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
			stage('Deploy to tomcat'){
				steps{
					sh 'cp target/com.ms.calc.war /home/da/tomcat7/webapps/'	
				}
			}
		}
}
