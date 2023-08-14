### Terraform Exercise solution  


### Installation  
To install the infrastructure, run the following commands in a terminal:  
    
```
git clone https://gitlab.com/sela-1090/students/lioratari/terraform.git  
    
cd terraform-infrastructure  
```
Then, open a terminal in the terraform directory and run the following command:  
    
```
terraform init  
```
Next, you will need to provide a password for your database. You can do so by running:
    
```
terraform plan --var="db_password=your_db_password_here"
terraform apply --var="db_password=your_db_password_here"
```
#### NOTE
you can run the above commands without the --var flag. You will be prompted to insert a password for the database.

![architecture](map.png)


