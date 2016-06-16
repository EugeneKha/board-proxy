FROM nginx:alpine
ADD ./src /usr/share/nginx/html
ADD ./nginx /etc/nginx


RUN ["mkdir", "-p", "/usr/share/nginx/www/cache"]


EXPOSE 8080