pipeline{
    agent any
    tools {
         terraform 'terraform-11'
    }
    stages{
        stage('Git checkout'){
           steps{
               git credentialsId: 'gnana03', url: 'https://github.com/gnana03/iac-demo'
           }
        }
        stage('Terraform Init'){
            steps{
            sh label: '',script:'terraform init'
            }
        }
        stage('Terraform Apply'){
            steps{
            sh label: '',script:'terraform apply --auto-approve'
           }
        }
   }
}
