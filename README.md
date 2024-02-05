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