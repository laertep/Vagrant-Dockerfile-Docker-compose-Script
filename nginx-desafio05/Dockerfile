FROM nginx:latest
ENV NGINX_DESAFIO05 /etc/nginx/conf.d/default.conf
COPY ./nginx.conf NGINX_DESAFIO05
ADD ./index.html /usr/share/nginx/html/
EXPOSE 80
LABEL description="Imagem nginx desafio05"
