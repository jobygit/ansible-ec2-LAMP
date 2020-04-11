# ansible-ec2-LAMP

This playbook will create a security group with ssh port open and spin up an Ec2 instance along with LAMP configured in the Ec2

##Prerequisites


#1.Install Ansible on a linux machine and setup it as Ansible-master(I have setup in my local linux machine)
#2.Install Python boto library
#3.Create an IAM Role with ec2fullaccess policy and configure the user in the ansible master machine



### vars_files:
#### aws_keys.yml\
  aws_access_key:\
  aws_secret_key:\
  
#### mysql.vars\
---\
mysql_root_password: mysqlroot123\
mysql_database: wordpress\
mysql_user: wpuser\
mysql_password: wpuser123

	
