FROM seanpublic/nginx:tiny
LABEL org.opencontainers.image.authors="gabor.strenzinger@gmail.com"
LABEL org.opencontainers.image.source=https://github.com/stenzing/container-fundamentals
LABEL org.opencontainers.image.description="Containter Fundamentals - Static Website Image"
LABEL server_type="edge_server"
LABEL org.opencontainers.image.licenses=APACHE2
COPY config/nginx.conf /etc/nginx/
COPY web_content/ /var/www
EXPOSE 80
