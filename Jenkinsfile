pipeline {
	agent none
    stages {
  
        stage('Build'){   
		    agent {
			    dockerfile {
				    dir 'swe'
			}
            steps{
                sh 'cat /etc/lsb-release'
            }
        }
    }
}
