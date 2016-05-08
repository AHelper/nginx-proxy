nginx: nginx
dockergen: docker-gen -watch -only-exposed -interval 5 -notify "nginx -s reload" /app/nginx.tmpl /etc/nginx/conf.d/default.conf
