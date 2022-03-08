
pipeline{
  agent any
  stages{
    stage('test'){
      steps{
        sh 'cd /home/ec2-user/DevSecOpsApp/DevSecOpsApp'
        sh 'sudo docker run --rm -i hadolint/hadolint < ./Dockerfile'
      }
      }
     }
    }
