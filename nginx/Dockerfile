FROM nginx:1.17.9-alpine

COPY static /opt/netbox/netbox/static
COPY nginx.conf /etc/netbox-nginx/nginx.conf

CMD nginx -c /etc/netbox-nginx/nginx.conf
