# Caddy Base Image
Simple Caddy Base Docker Image
### Defaults
* Default Caddyfile: `/etc/Caddyfile`
* Default Site: `/var/www/`
### Build it
```
docker build -t pablitoam:caddy-base:latest .
```
### Run it
```
docker run -p 8080:80 pabitoam:caddy-base:latest
```
### Custom Caddyfile

Extend the image and copy your caddy file into `/etc/Caddyfile`








