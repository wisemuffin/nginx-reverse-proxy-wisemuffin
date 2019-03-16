# Web server ngninx

TSL certificiates on host server (not in docker) /etc/letsencrypt/live/wisemuffin.com

renew every 90 days. Automaticall scheduled by crontab

domain: namecheap
tsl cert: certbot

## migration to a new server

- change all proxy_pass to new server

### lets encrypt with nginx

https://medium.com/@pentacent/nginx-and-lets-encrypt-with-docker-in-less-than-5-minutes-b4b8a60d3a71
curl -L https://raw.githubusercontent.com/wmnnd/nginx-certbot/master/init-letsencrypt.sh > init-letsencrypt.sh

then

sudo ./init-letsencrypt.sh
