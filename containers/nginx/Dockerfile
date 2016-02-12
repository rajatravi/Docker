FROM nginx
EXPOSE 443
COPY default.conf /etc/nginx/conf.d/default.conf
RUN mkdir /etc/nginx/ssl/
ADD nginx.crt /etc/nginx/ssl/
ADD nginx.key /etc/nginx/ssl/
