# certbot-docker-haproxy
### if port 80 in use, find which process using it:
* sudo lsof -i :80
* kill processes
### sudo -H /opt/letsencrypt/letsencrypt-auto certonly --standalone -d www.mydomain.com
