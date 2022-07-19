```
#!/bin/bash

yum update -y
yum install httpd -y
service httpd start
systemctl httpd start
systemctl httpd enable
echo "Hi, User20" > /var/www/html/index.html
```
