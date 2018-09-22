# Aria install 
1. Install aria2 client
> sudo apt-get install aria2
2. Copy config file 
> /home/pi/.aria2/aria2.session and /home/pi/.aria2/aria2.conf
3. Prepare font-end server
> - sudo git clone git@github.com:xckai/webui-aria2.git /var/www/aria
> - mv nginx file to /etc/nginx/sites-enabled  and restart nginx
4. Done