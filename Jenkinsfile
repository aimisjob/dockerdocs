pipeline {
	agent none
    stages {
  
        stage('Build'){   
		    agent {
			    dockerfile {
				   filename "custom"
			}
		    }
            steps{
                sh 'cat /etc/lsb-release'
            }
        }
    }
}
