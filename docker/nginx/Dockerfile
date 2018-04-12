FROM nginx:latest

ADD main.conf /etc/nginx/main.conf
ADD nginx.conf /etc/nginx/nginx.conf
ADD shared.conf /etc/nginx/shared.conf
ADD conf.d /etc/nginx/conf.d/
ADD sites-available /etc/nginx/sites-available

RUN ln -s /etc/nginx/sites-available/main.conf /etc/nginx/sites-enabled/main.conf
