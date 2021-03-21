pipeline {
	agent none
    stages {
  
        stage('Build'){   
		    agent {
			    dockerfile {
				   additionalBuildArgs '--tag pavan:talks'
			}
		    }
            steps{
                sh 'cat /etc/lsb-release'
            }
        }
    }
}
