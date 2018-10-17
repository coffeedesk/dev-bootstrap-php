FROM nginx:latest

COPY ./docker/nginx/site.tmpl /etc/nginx/conf.d/site.tmpl

CMD /bin/bash -c "envsubst < /etc/nginx/conf.d/site.tmpl > /etc/nginx/conf.d/site.conf && nginx -g 'daemon off;' || cat /etc/nginx/conf.d/site.conf"
