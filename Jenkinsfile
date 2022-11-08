pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ec2 --template-body file://Daroju_ec2.yml --region 'us-east-1'"
              }
             }
            }
            }
