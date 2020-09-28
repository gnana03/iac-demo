Objective : To integrate Terraform in Jenkins pipeline

# Pre-requisites

Jenkins running on ec2 instance
iac project written in terraform
Terraform is installed on Jenkins plugins

# Steps to create a pipeline
- Go to Jenkins--> New Item --> { Give a name } --> Pipeline --> save
- Go to Pipeline and provide the pipeline steps defined in Jenkinsfile
- Add github credentils and modify the Jenkinsfile according to the credentials given
-  Locate Jenkins Credentials
- Save and apply changes
- Build now


