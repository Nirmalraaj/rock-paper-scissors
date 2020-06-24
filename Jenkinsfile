pipeline{
	agent any
	
	
	def mvn = tool (name: 'maven', type: 'maven')
	stages {
		stage('deploy the maven'){
			steps {
				echo 'maven is deploying'
				
				mvn tomcat7:deploy
			}
		}
		
		
	}
}
