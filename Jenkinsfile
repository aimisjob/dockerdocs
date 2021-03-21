pipeline {
  agent none
  options {
    checkoutToSubdirectory('gulabi')
  }
  stages{
    stage('build') {
      agent {
        dockerfile {
          customWorkspace '/var/lib/jenkins/workspace/pl_myexp/gulabi'
        }
      }
      steps {
        sh 'cat /etc/lsb-release'
    }
  }
}
}
