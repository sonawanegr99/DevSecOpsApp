
pipeline{
  agent any
  stages{
    stage('test'){
      steps{
        sh '''#!/bin/bash
        
                 sudo docker run --rm -i hadolint/hadolint < ./Dockerfile
         '''
      }
      }
     }
    }
