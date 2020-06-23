pipeline{
	agent any
	
	
	options {
		timestamps()
		
		
	}
	stages {
		stage('deploy the maven'){
			steps {
				echo 'maven is deploying'
				
				mvn tomcat7:deploy
			}
		}
		
		
	}
}
