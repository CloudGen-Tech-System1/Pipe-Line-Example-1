pipeline {
    agent any

    stages {
        stage('Code Pull') {
            steps {
                echo 'Pulling codeFrom GitHub Stage'
            }
        }
        stage ('Code Test')
        {
        	steps{
        		echo 'Code Testing Stage'
        	}
        }
        stage ('Code Build')
          {
        	steps{
        		echo 'Code Build Stage'
        	}
        }
        stage ('War Deploy'){
        	steps{
        		echo 'War Deploy into Prod/Test Server'
        	}
        }

    }
}
