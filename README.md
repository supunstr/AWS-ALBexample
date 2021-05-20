.
# AWS-ALBexample

First Instance
#!/bin/bash;
yum install httpd -y;
systemctl enable httpd
mkdir /var/www/html/orders/
echo "<h1> This is Order App</h1>" > /var/www/html/orders/index.html
systemctl start httpd

Second instance
#!/bin/bash
yum install httpd -y
systemctl enable httpd
mkdir /var/www/html/bill/
echo "<h1> This is Order App</h1>" > /var/www/html/bill/index.html
systemctl start httpd
 
