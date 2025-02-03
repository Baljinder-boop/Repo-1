pipeline {
	agent any
	stages {
		stage('Build') 
		{
			steps {
				echo 'Build World hjkhgkjg'
				}
		}
		stage('Deploy') 
		{
			steps 
				{
				echo 'Depoly World'
				}
		}	
		stage('Test') 
		{
			steps 
			{
				echo 'Test World'
			}
		}
		}
		post
		{
			always
			{
				emailext body:'Summary' , subject:'Pipeline Status' , to:'baljinderkaur659192@gmail.com'
			}
		}
	}			
			
				
