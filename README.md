# CLO 835 Assignment1

##Student Name: Kasun Athugoda
##Studnet ID: 124457235

---

###1. Deploying the AWS infrastructure for the docker environment.
```bash
cd terraform
ssh-keygen -t rsa -f clo835app
terraform init
terraform plan
terraform apply --auto-approve
```

*To destroy the terrafrom environment*
`terraform destroy --auto -approve`


###2. Git hub Actions

 -   i. Update the authentication tokens in github to run github actions.
 -  ii. Merge a new branch with `prod` branch to execute the github action DEPLOY ECR.
 - iii. Update the ~/.aws/credentials with session details in the EC2 instance.
          `aws configure` and then update the details.
 -  iv. Run the DB docker.
 -   v. Execute the environement variables
 -  vi. Run the application docker.
