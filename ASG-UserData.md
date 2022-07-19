```
#!/bin/bash
echo "<br> $(hostname -f)" >> /var/www/html/index.html
echo "<br><img src=\"https://d2n25aw1m1kdju.cloudfront.net/BAYC.jpg\">">> /var/www/html/index.html

systemctl start httpd
systemctl enable httpd
```
