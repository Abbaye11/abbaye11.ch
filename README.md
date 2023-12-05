### Let's Encrypt/Certbot docker
* https://phoenixnap.com/kb/letsencrypt-docker
* https://pentacent.medium.com/nginx-and-lets-encrypt-with-docker-in-less-than-5-minutes-b4b8a60d3a71


### Récupérer/renouveler le certificat
> docker compose run --rm  certbot certonly --webroot --webroot-path /var/www/certbot/ --dry-run -d 'kestra.abbaye11.ch'

### Démarrer
> docker compose up -d

### Rdémarrer 
> docker compose restart