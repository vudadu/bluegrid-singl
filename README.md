# Wordpress with MySQL on one ec2 and one RDS instance

Prerequisites is installed teraform and git 

Steps to build infrastucture on AWS:
```
git clone https://github.com/vudadu/bluegrid-singl.git
cd bluegrid-singl
```
Edit accsess and secret key for AWS User in main.tf
```
access_key = "ACCESS_KEY_HERE"
secret_key = "SECRET_KEY_HERE"
```
Initialize and build infrastucture
```
terraform init
terraform apply
```
to destroy infrastucture
```
terraform destroy
```



# Simple infrastucture diagram

![image](https://user-images.githubusercontent.com/44177257/179164071-ec72ed82-8de5-49bd-bf40-d15a1e3d2922.png)
