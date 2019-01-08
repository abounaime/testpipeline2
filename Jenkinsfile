pipeline{
	
	agent any
	
	tools {
		maven 'maven_3_6_0'
	}	
	
	stages{
		
		stage('Compile stage'){
			
			steps{
				bat 'mvn clean compile'
			}
		}
		
		stage('Test stage'){
			steps{
				bat 'mvn test'
			}
		}
		
		stage('Deployement stage') {
			steps{
				bat 'mvn deploy'
			}
		}
	}
}