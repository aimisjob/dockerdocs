pipeline {
	agent none
    stages {
  
        stage('Build'){   
		    agent {
				dockerfile true
			}
            steps{
                sh 'cat /etc/lsb-release'
            }
        }
    }
}
