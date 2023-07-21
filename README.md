# GCP-Startup-Script
Here is GCE Startup Script that you can copy and paste for your needs

```
#!/bin/bash
apt update 
apt install apache2
echo "Hello world from $(hostname) $(hostname -i)" > /var/www/html/index.html
```
