
pipeline{
  agent any
  stages{
    stage('test'){
      steps{
        sh '''#!/bin/bash
                  docker run --rm -i hadolint/hadolint < ./Dockerfile
         '''
      }
      }
     }
    }
