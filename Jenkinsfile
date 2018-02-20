pipeline {
	agent any
	
	stages {
		stage ('Compile Stage') {
			
				steps {
					sh 'whereis mvn'
				    sh 'mvn clean compile'					  
					  }
							}
           		stage ('Testing Stage') {
			
				steps {
				    sh 'mvn test'					  
					  }
							}
           		
           		
				
				}

			}
