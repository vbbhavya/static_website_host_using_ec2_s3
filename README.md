# static_website_host_using_ec2_s3
This is a Static website hosting using aws ec2 -and s3 bucket

 create and launch instance with amazon linux ami
 
 create bucket in s3 and then upload zip file of all source code attached demo file 
 
 set bucket and object as public access

 connect instance

 and run following commands

 sudo su
yum update -y
yum install httpd -y
cd /var/www/html
wget s3_Object_URL
unzip name.zip
mv SubFolder_Name/* .
service httpd start

Finally, copy public IP of your instance and paste it in the web browser

 
 
 

