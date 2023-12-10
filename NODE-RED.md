# Node-RED Tips

Setup a new Node-RED Authenticated user on NGINX (web-proxy).

```bash
docker-compose exec nginx bash
htpasswd /etc/nginx/authdata/nodered/.htpasswd newuser
```
