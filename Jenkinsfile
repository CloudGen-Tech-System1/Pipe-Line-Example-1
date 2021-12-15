pipeline
{
	agent any
	tools
	{
	maven "Maven"
	}
	stages{
		stage('Code Checkout'){
			steps{
				git branch: 'main', url: 'https://github.com/CloudGen-Tech-System1/Pipe-Line-Example-1.git'

			}
		}
		stage('Execute Maven'){
			steps{
				sh 'mvn package'
			}
		}
	}
}
