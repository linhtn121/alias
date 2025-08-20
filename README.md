# alias
# web-aliases.sh
## alias site-status='systemctl status nginx apache2'
### alias check-vhosts='nginx -T | grep server_name'
### alias ssl-expire='openssl x509 -in /etc/ssl/cert.pem -noout -dates'
### alias site-backup='tar -czf site-$(date +%Y%m%d).tar.gz /var/www/'

# db-aliases.sh  
### alias mysql-status='systemctl status mysql'
### alias mysql-size='mysql -e "SELECT table_schema AS DB, ROUND(SUM(data_length+index_length)/1024/1024,2) AS MB FROM information_schema.tables GROUP BY table_schema;"'
### alias backup-all-db='mysqldump --all-databases > all-db-$(date +%Y%m%d).sql'

# docker-aliases.sh
### alias dps='docker ps --format "table {{.Names}}\t{{.Image}}\t{{.Status}}\t{{.Ports}}"'
### alias dlog='docker logs -f'
### alias dexec='docker exec -it'
### alias dclean='docker system prune -f'
