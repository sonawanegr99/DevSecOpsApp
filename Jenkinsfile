
pipeline{
  agent any
  stages{
    stage('test'){
      steps{
        bash '''
        #!/bin/bash
        cd /home/ec2-user/DevSecOpsApp/DevSecOpsApp
        sudo docker run --rm -i hadolint/hadolint < ./Dockerfile
        '''
      }
      }
     }
    }
