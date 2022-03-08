
pipeline{
  agent any
  stages{
    stage('test'){
      steps{
        sh '''
        #!/bin/bash
        cd /home/ec2-user/DevSecOpsApp
        sudo docker run --rm -i hadolint/hadolint < ./Dockerfile
        '''
      }
      }
     }
    }
