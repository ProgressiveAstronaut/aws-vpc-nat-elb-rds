Installation Instructions for ubuntu 14.04
-----------------------------------------
* apt-get update
* apt-get -y install python-pip
* pip install boto
* pip install awscli
* dpkg -i ansible_2.0.0.deb
* apt-get -f install
* git clone https://github.com/s1lv3r40/aws-vpc-nat-elb-rds.git

Export the variables before running the playbook
------------------------------------------------------------------------------------
* export AWS_ACCESS_KEY_ID=<key id>
* export AWS_SECRET_ACCESS_KEY=<access key>
* export EC2_REGION=<region>

#Configuration Variables
They are located in vars/aws_vars.yml.
You can configure them according your needs. 
Please define dbpassword value.
