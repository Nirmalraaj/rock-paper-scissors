pipeline{
	agent any
	
	
	options {
		timestamps()
		
		
	}
	stages {
		stage('deploy the maven'){
			steps {
				echo 'maven is deploying'
				echo 'mvn echo:echo'
				echo 'mvn tomcat7:deploy'
			}
		}
		
		
	}
}
