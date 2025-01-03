README.md
■Set-Up
1. Create S3 for tfstate
2. Generate public and private key
3. Write resource's variables in terraform.tfvars

■Resources
<br />
Network
<br />
EC2
<br />
ACM
<br />
ALb x 1(HTTP & HTTPS Listener)
<br />
ACM
<br />
Route53
<br />
CloudFront
<br />
S3

■Deploy
1. Move to direstory
2. terraform init
3. terraform plan
4. terraform apply

■About Github Actions
1. terraform plan will be executed on main branch
2. merge dev branch into main branch
3. 