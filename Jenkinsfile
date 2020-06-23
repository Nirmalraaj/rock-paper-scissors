pipeline{
	agent any
	
	
	options {
		timestamps()
		
		
	}
	stages {
		stage('deploy the maven'){
			steps {
				echo 'maven is deploying'
				mvn echo:echo
				mvn tomcat7:deploy
			}
		}
		
		
	}
}
