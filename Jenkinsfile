
pipeline{
  agent any
  stages{
    stage('test'){
      steps{
        sh '''#!/bin/bash
                 cd /home/ec2-user/DevSecOpsApp/DevSecOpsApp
                 ls
                 docker run --rm -i hadolint/hadolint < ./Dockerfile
         '''
      }
      }
     }
    }
