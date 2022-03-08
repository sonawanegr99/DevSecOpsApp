
pipeline{
  agent any
  stages{
    stage('test'){
      steps{
        sh '''
        #!/bin/bash
        sudo docker run --rm -i hadolint/hadolint < ./home/ec2-user/DevSecOpsApp/DevSecOpsApp/Dockerfile
        '''
      }
      }
     }
    }
