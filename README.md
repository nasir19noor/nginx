# nginx

add ssl cert
```
sudo certbot certonly --standalone -d xxx.nasir.id
```
symlink
```
sudo ln -s /etc/nginx/sites-available/grafana.nasir.id /etc/nginx/sites-enabled/
```
